#Lab Report 1        
=========

![Image](intro.png)

cd: used to switch the current working directory to the given path
---------

__1.using no arguments__

![Image](cd1.png)

- the working directory is `/home`

- there was no output, as it was only accessing the home directory. So there is no path to any of the files, so its called no argument. And no filesytem yet

- no error

__2.using a directory as argument__

![Image](cd2.png)

- the working directory now is `/home/lecture1`

- there was no output, as it was only accessing the `/lecture1` directory now. So now there is a argument like `/lecture1`. Doing that we are able do open the folder of `/lecture1` by the filesystem

- no error

__3.using a file as arugment__

![Image](cd3.png)

- the working directory now is `/home/lecture1`

- So now we tried the argument like `README`.However, we get an error with that, because `cd` is only used to acess directory, but `README` is a file

- error

ls: used to list the files and folders the given path
---------

__1.using no arguments__

![Image](ls1.png)

- the working directory is `/home`

- we get a list of the home directory `/home`, that is only the `/lecture1` folder. So by the filesystem we get the `/lecture1` folder

- no error

__2.using a directory as argument__

![Image](ls2.png)

- the working directory is `/home`

- So using the arguement `/lecture1`, we get a list of the directory `/lecture1`, so we get the folder like messages and the file like `Hello.class`, `Hello.java`, `README`. So by the filesytem we get to know what files we have

- no error

__3.using a file as arugment__

![Image](ls3.png)

- the working directory is `/home`

- So using the argument of `README`, the `README` file was the last file. So after that there is no more list. So we get an error, because we are trying to find a list of a file inside a file

- error

cat: used to print the contents of one or more files given by the paths
---------

__1.using no arguments__

![Image](cat1.png)

- the working directory is `/home`

- using no argument, when we used `cat` everthing that we write, it will be the output

- no error

__2.using a directory as argument__

![Image](cat2.png)

- the working directory is `/home`

- when we use the argument as a directory,we get an error. Because `cat` use only for read the file, and `/lecture1` is a directory

- error

__3.using a file as arugment__

![Image](cat3.png)

- the working directory is `/home`

- when we use the file as argument, its print what was written on the `README` file. So basically give us the output on what was written in the file

- no error




