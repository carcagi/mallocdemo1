# mallocdemo1

* Write the memory diagram for the program in mallocDemo1.c. Specifically, (1) show where wordArray is stored; (2) where is word pointing to before and after malloc; (2) what is stored in the word? (3) What happens to wordArray after free? Compare this memory allocation with mallocDemo1.c

* In mallocDemo1.c, what happens if we add the below code after malloc ?

word = wordArray;
What do you expect when free function is called?
* In mallocDemo1.c, what happens if we add the below code instead of the exsting strcpy ?

strcpy(word, wordArray[3]);
Assume that the user has entered a wordArray of length 15 (say "pointers are fun")
* In demo1.c, what happens if we dont free word?

* When does malloc return NULL? Write a sample program to simulate 3 cases where malloc returns NULL. (man malloc)

* Dead objects and dangling pointers: What happens if we use word after the free call? Remember we have free'd the memory, but we are trying to access it. What should happen?

* Memory leaks: Say, I have a function
