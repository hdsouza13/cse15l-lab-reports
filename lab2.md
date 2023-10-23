Lab Report 2

Part 1
```
import java.io.IOException;
import java.net.URI;
import java.util.ArrayList;

class Handler implements URLHandler {
    // The one bit of state on the server: a number that will be manipulated by
    // various requests.
    ArrayList<String> message = new ArrayList<String>();
    int num = 0;
    public String handleRequest(URI url)
    {
        if (url.getPath().equals("/")) 
        {
            return String.format("Number: %d", num);
        } else if (url.getPath().equals("/increment")) {
            num += 1;
            return String.format("Number incremented!");
        } else {
            if (url.getPath().contains("/add-message"))
            {
                String[] parameters = url.getQuery().split("=");
                if (parameters[0].equals("s"))
                {
                    String output = "";
                    int counter = 1;
                    message.add(parameters[1]);
                    for(int i = 0; i < message.size(); i++)
                    {
                        output += counter + ". " + message.get(i) + "\n";
                        counter++;
                    } 
                    return output;
        
                }
            }
        }
            return "404 Not Found!";
        }
    }


class NumberServer {
    public static void main(String[] args) throws IOException {
        if(args.length == 0){
            System.out.println("Missing port number! Try any number between 1024 to 49151");
            return;
        }

        int port = Integer.parseInt(args[0]);

        Server.start(port, new Handler());
    }
}
```
![Image](ph25.png)

- The `/add-message` method is being called

- The revelent argument for this method is the string "Hello"

![Image](ph26.png)

- The `/add-message` method is being called

- The revelent argument for this method is the string "How are you"


Part 2

The path to the private key for your SSH key for logging into ieng6 (on your computer or on the home directory of the lab computer)





  


