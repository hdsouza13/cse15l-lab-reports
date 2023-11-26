Lab 4
=========

Log into ieng6
---
![Image](phlab4.1.png)

ssh cs15lfa23hr@ieng6.ucsd.edu ```<enter>```

Clone your fork of the repository from your Github account (using the SSH URL)
---
![Image](lab4ph1.png)

git clone git@github.com:hdsouza13/lab7.git ```<enter>```

Run the tests, demonstrating that they fail
---
![Image](lab4ph2.png)

bash test.sh ```<enter>```

Edit the code file ListExamples.java to fix the failing test (as a reminder, the error in the code is just that index1 is used instead of index2 in the final loop in merge)
---

vim TestExamples.java

43j

11l

x

a 

<-

2

<esq> 

:qw 

<enter>

j: the number of lines you want to go down

l: the number of spaces you want to go to the right

x: delete a element

a: append a element

<esq> to leave the edit mode

:qw -> to save what you edit

Run the tests, demonstrating that they now succeed
---
![Image](lab4ph3.png)

bash test.sh ```<enter>```

Commit and push the resulting change to your Github account
----
![Image](lab4ph4.png)
![Image](lab4ph5.png)

git add ListExamples.java ```<enter>```
git commit -m "Success" ```<enter>```
git push ```<enter>```
