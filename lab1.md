#Lab Report 1        
-
__cd: used to switch the current working directory to the given path__ 

1.using no arguments

![Image](cd1.png)

- the working directory is /home

- there was no output, as it was only accessing the home directory

2.using a directory as argument

![Image](cd2.png)

- the working directory now is /home/lecture1

- there was no output, as it was only accessing the lecture1 directory now

3.using a file as arugment

![Image](cd3.png)

- we get an error with that, because cd is only used to acess directory, but README is a file

__ls: used to list the files and folders the given path__ 

1.using no arguments

![Image](ls1.png)

- the working directory is /home

- we get a list of the home directory /home, that is only the lecture1 folder

2.using a directory as argument

![Image](ls2.png)

- the working directory is /home

- we get a list of the directory /lecture1, so we get the folder like messages and the file like Hello.class, Hello.java, README

3.using a file as arugment

![Image](ls3.png)

- the README file is the last file, so there is no more list after that, then the path was printed

__cat: used to print the contents of one or more files given by the paths__

1.so the file README is the last file, so there is no more list after that, so the output was the path

![Image](cat1.png)

- the working directory is /home

- when we used cat everthing that we write, it will be the output

2.using a directory as argument

![Image](cat2.png)

- we get an error, because cat use only for read the file, and lecture1 is a directory

3.using a file as arugment

![Image](cat3.png)

- the working directory is /home

- its print what was written on the README file




