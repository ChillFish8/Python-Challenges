# Challenges 11-20: "A steepening slope"

11.	Ask the user for a number which must be between 1 and 26 (inclusive). Validate the input - do not accept invalid responses.
Using a calculation based on ASCII codes, display the letter of the alphabet that could be found at this position. For example,
if the user enters 4 then you should display the letter D.


12.	Ask the user for a number which must be between 32 and 126. Validate the input - do not accept invalid responses. 
Display the character from the ASCII character set that corresponds to this code.


13.	Write a subroutine that receives a string. Validate that the string is in the format <letter><number> and only 2
characters long. The letter must be from A-C and the number must be from 1-3. Return a tuple that contains the value
False if the input was invalid or the indexes for the letter and the number. For example, if the input was "B3" the tuple
should be (1, 2). If the input was "bob" the tuple would be (False).


14.	Write a subroutine that receives an integer between 3 and 10 (inclusive). Using ASCII characters, draw a grid on the 
screen that has this number of rows and columns. If the passed value is not valid your subroutine should return False but
if it draws the grid it should return True.
 
 
15.	Modify the subroutine from the last challenge to accept two numbers. The first is for the number of rows they would 
like and the second for how many columns they would like. The numbers should be defaulted to 5. Both must be numbers
between 3 and 10. Draw a grid of the size entered by the user. Return False if the input is not valid or True if the grid was drawn.


16.	Write a subroutine to receive a sentence as a string. Split this into a list containing strings for each word from 
the sentence. For example - `"Hello world" -> ["Hello", "world"]`. Return the list with the words in it. 
**YOU ARE NOT ALLOWED TO USE THE BUILT-IN FUNCTION SPLIT**.


17.	Write a subroutine that receives a string. The string must be at least 4 characters long. Determine if this is a
palindrome (reads the same forwards as it does backwards). Return True if the string is a palindrome or False if it is 
too short or not a palindrome.


18.	Write a subroutine that will count the number of a given letter in a string. Now wrap this in a program that will 
ask the user to type a sentence - validate that it is at least 20 characters long. Ask them for a letter - validate that 
they provided a letter. Using the subroutine, count how many times the letter appears in the sentence regardless of case.


19.	The isalpha and isdigit string methods determine if a string contains only letters or only numbers. 
Write your own isfloat subroutine that will determine if a string contains a sequence of characters that can be converted into a float.
It shoudl return True or False. Now use your subroutine to determine if a string provided by the user can be converted and then 
do the conversion. You need to make sure it can handle negative numbers. 
<br>**YOU MUST NOT USE THE BUILT-IN FUNCTION FLOAT.**


20.	Write a subroutine to convert from Fahrenheit to Centigrade. <br> Write another to do the opposite. `F -> C:  5/9 x (F – 32). C -> F:  (C x 9/5) + 32`. Your subroutines will be passed a number and should return a number. Make sure they validate the data type of the input and if it is not a number return an error value of -999
