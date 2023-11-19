
Log into ieng6
ph

Clone your fork of the repository from your Github account (using the SSH URL)
ph

Run the tests, demonstrating that they fail
ph

Edit the code file ListExamples.java to fix the failing test (as a reminder, the error in the code is just that index1 is used instead of index2 in the final loop in merge)
vim TestExamples.java
43j 11l x a <- 2 <esq> :qw <enter>

j: the number of lines you want to go down
l: the number of spaces you want to go to the right
x: delete a element
a: append a element
<esq> to leave the edit mode
:qw -> to save what you edit

Run the tests, demonstrating that they now succeed
ph

Commit and push the resulting change to your Github account
ph
