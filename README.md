# Star-Repetition-2
write a program that reads a word and prints stars (*) equal to the length of the word.

Input: Queue

Output: Q****

Explanation:

Step 1: Get the input First, we need to get the input from the user, which is a word. Here, input() is a function that allows the user to enter a word, and word is a variable that stores the entered word.

Step 2:  Find the length of the word
Next, we need to find out how many letters are in the word. We can do this using the len() function.
len() is a function that gives us the number of characters in a string. Here, word_length is a variable that will store the length of the word.

Step 3:Get the First Character and Number of Stars
Now, we need to get the first character of the word and calculate the number of stars we need to print. We can do this using string indexing and subtraction.
word[0] gives us the first character of the word, and word_length - 1 gives us the number of stars we need to print.

Step 4: Generate the Result
Now that we have the first character and the number of stars, we can generate the result. To do this, we use the * operator in Python and string concatenation.


Step 5: Print the Result
Finally, we print the result by using the print() function in Python.
This print() function will display the value of the result variable, which is the first character followed by the star pattern.

