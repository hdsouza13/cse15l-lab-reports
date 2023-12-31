Lab 4
=========

Log into ieng6
---
![Image](phlab4.1.png)

```ssh<space>cs15lfa23hr@ieng6.ucsd.edu<enter>```

So I use the ssh to login in the remote server of ieng6, and I didnt need to use my password because I already setup it using the ```ssh-keygen```, the authentication key.

Clone your fork of the repository from your Github account (using the SSH URL)
---
![Image](lab4ph1.png)

```git<space>clone<space>git@github.com:hdsouza13/lab7.git<enter>```

Before I do this command, I forked my github repository on my browser and copy the text as a ssh clone. So then I git clone my git hub ssh url of my github repository. 

I already had the ssh key setup for my github, so no further input was needed to clone the repositoy.


After I clone my repository, I used the ```cd lab7``` to set the working directory and ```ls``` to view what it is inside it

```cd<space>lab7<enter>```

```ls<enter>```

![Image](ph9.png)

Run the tests, demonstrating that they fail
---
![Image](lab4ph2.png)

```bash<space>test.sh<enter>```

I run the bash test.sh to show that the code was incorrect and fail


Edit the code file ListExamples.java to fix the failing test (as a reminder, the error in the code is just that index1 is used instead of index2 in the final loop in merge)
---

```vim<space>ListExample.java```

So I used the vim command, so I can edit and correct the file, using my terminal

![Image](ph10.png)

Inside vim
---

```/index1<enter> n ```

To go to the part that I need to fix, I first type ```/index1``` and enter to search for index1.Then I pressed n some times until I finally able to find the "index1" that need to be changed to "index2"

```e r 2<esq>:wq<enter>```

```e``` is to go to the end of the word

```r2``` replace the last character in the word to be a “2”, to make the word “index2”

```:wq<enter>``` to save my changes and exit out of vim

![Image](phlab4.7.png)

Run the tests, demonstrating that they now succeed
---
![Image](lab4ph3.png)

```bash<space>test.sh<enter>```

I run the bash test.sh to show that the code was correct and succeed

Commit and push the resulting change to your Github account
----
![Image](lab4ph4.png)
![Image](lab4ph5.png)

```git<space>add<space>ListExamples.java<enter>```

I type ```git add```, this adds my file ```ListExamples.java``` to be staged.

```git<space>commit<space>-m<space>"Success"<enter>```

 I type ```git commit``` with the commit message using the -m option, that will create the commit with the message "Sucess".

```git<space>push<enter>```

Then finally ```git push``` is the final command I use to update the remote git repository.


