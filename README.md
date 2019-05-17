<h1> Malloc Lab Keegan Mullins

<h3> The purpose of this lab was to create a type of dynamic memory allocator for c.

<h3> The bulk of the project is located in the "mm.c" file. The rest of the files are meant for testing or contain other supporting functions.

<h3> My code works by allocating blocks of varying size in order to store different sizes of data according to their own respective sizes. The blocks have tags indicating the size of the data being stored such that the blocks may be traversed quickly without having to scan the data inside of them. (effectively a linked list)

<h3> Most of the code in this project is my own, however the basic shell of the project itself was provided by my computer systems class. Any function that says "you need to provide this" inside of the "mm.c" file was coded by myself. Almost everything else was coded by the people running the class.
