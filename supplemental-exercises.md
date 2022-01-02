# Supplemental Exercises


1. Write a function that converts temperatures from Fahrenheit to Celsius.  The function should take the temperature in Fahrenheit as an argument and return the temperature in Celsius.  The function itself should produce no output to the screen.
1. Write a function that converts distances from miles to kilometers.  The function should take the distance in miles as an argument and return the distance in kilometers.  The function itself should produce no output to the screen.
1. The coffee shop in the library sells coffee for $10.50 a pound plus the cost of shipping.  Each order ships for $0.86 per pound plus $1.50 fixed cost for overhead.  Write a function that calculates the cost of an order given the number of pounds ordered.
1. Write a function that computes the total amount of money you would receive if you received a penny a day doubled a day for a month.  For example, on the first day you would get $0.01, on the second day you would get $0.02 (for a total of $0.03), on the third day you would get $0.04 (for a total of $0.07), and so on.  Your function should take the number of days in the month as an argument and return the total amount of money you would receive.  Furthermore, the function should print out the amount received for each day and the current total up to that day.
1. Write a function that prompts the user for input, changes the input so that it is in all capital letters and prints it out.  The function should continue to prompt for input until the user enters `quit`.
1. Write a function that performs division and prints out the quotient and the remainder.  The function should take the numerator and denominator as arguments and not return anything.  Note that the function should not simply perform division and display the result as a decimal.  Below is a sample execution of the function.

		>>> divide( 7, 3 )
		Quotient=[2] Remainder=[1]
		>>>
    Modify the above function to return the quotient and the remainder instead of printing them out.  Below is a sample execution of the modified function.
    
		>>> (quotient, remainder) = divide( 7, 3 )
		>>> print( quotient, remainder )
		2 1
1. Write an interactive Python calculator program.  The program should allow the user to type a mathematical expression, and then print the value of the expression.  The program should continue to accept user input until the user types in `quit`.  Once you have the basic program working, try to improve it so that it doesn’t break when a user enters an invalid expression.
1. Write a function to find the sum of the squares of the first n positive integers.  The function should take the number n as an argument and return the sum.
1. Python has an operator called `in` that determines if a character or a substring is contained in a larger string.  It returns True if the character or substring is in the larger string, otherwise, it returns False.  Write a function called in_string that implements the same functionality.
1. Write a function that prompts a user to enter their first and last names.  The function should then print a computer username consisting of the first letter of their first name and the first seven letters of their last name.
1. Rewrite the previous function to read the first and last names from a file and create usernames for everyone in the file.
1. Write a function that accepts a list of numerical grades formatted as a percentage as an argument.  The function should return (not print) a list of letter grades equivalents.  Use the grading scale specified in the syllabus for this course.
1. Write a function that computes the mean word length in a String.  The string should be passed as an argument and the mean word length should be returned (not printed).
1. Write a function that accepts the current date as a string in the following format `MM/DD/YYYY` as an argument.  It should print out the full date as `MONTH DD, YYYY`.
1. A common utility on Unix/Linux systems is a small program called `wc`.  This program analyzes a file to determine the number of lines, words, and characters contained therein.  Write your own version of wc.  The program should accept a filename as input and then print three numbers showing the count of lines, words, and characters in the file.
1. Write a program which accepts a sequence of comma-separated numbers from the console and generates a list and a tuple which contains every number.  Suppose the following input is supplied to the program:

		34,67,55,33,12,98
		Then, the output should be:
		['34', '67', '55', '33', '12', '98']
		('34', '67', '55', '33', '12', '98')
    Write a program that accepts console input containing the name, age and height of a number people producing a list of tuples containing the information.  If the following information is given as input to the program:

		George,17,70
		Sally,18,65
		Bill,21,66
		Jenny,19,66
    Then, the output should be:

    	[(‘George’,17,70), (‘Sally’,18,65), (‘Bill’,21,66), (‘Jenny’,19,66)]

1. Modify the above program so that it filters out everyone that isn’t 18 years of age.  The output should be:

		[(‘Sally’,18,65), (‘Bill’,21,66), (‘Jenny’,19,66)]

    Write a function called distance that takes two (2) two-dimensional points and returns the distance between them.  Then, extend your function to use three-dimensional points.  Can you generalize it to take two points of any dimension?

