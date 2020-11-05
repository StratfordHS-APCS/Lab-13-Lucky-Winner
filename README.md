# Lab 13 - Lucky Winner

You would like to give away an awesome prize to one lucky person in the class selected at random.

1. Write a program that lets the user type in names. Each name that is entered should be stored in an ArrayList of type String. When the word "done" is entered then the program should stop asking for names. 
2. Make sure that duplicate names are not recorded in the ArrayList.  Only one entry per person!
3. Print a list of all contestants using a “for each” loop to display the contents of your ArrayList.
4. Then your program should generate a random number that could be any entry in the ArrayList and print out the name of the lucky winner.

There are not any tests for this lab.  Make sure it works, then turn it in.

**Randomness:**
To create a random integer between min and max (inclusive):
`(int)(Math.random() * ((max - min) + 1)) + min`