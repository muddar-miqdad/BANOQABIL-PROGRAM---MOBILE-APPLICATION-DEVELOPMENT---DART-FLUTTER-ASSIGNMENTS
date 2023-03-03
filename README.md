# AREA OF TRIANGLE USING THE FORMULA A = (b * h) / 2

DESCRIPTION:

A program that calculates the area of a triangle using the formula A = (b * h) / 2. This program prompt the user to enter the base and height of the triangle and then display the calculated area.

HOW IT WORKS:

1. We first import the dart:io library to use the stdin and stdout objects for user input and program output, respectively.

2. We prompt the user to enter the base of the triangle and store it as a double value in the base variable. We use the readLineSync() method to read the user's input from the command line and the double.parse() method to convert the user's input from a string to a double.

3. We do the same for the height of the triangle, storing the user's input as a double value in the height variable.

4. We calculate the area of the triangle using the formula A = (b * h) / 2 and store it as a double value in the area variable.

5. We use string interpolation to output the calculated area to the console in a user-friendly message.


# AVERAGE OF 2 FLOATING POINT NUMBERS

DESCRIPTION:

A program that prompts the user to enter two floating-point numbers and then calculates their average. The program should display the result with two decimal places.

HOW IT WORKS:

1. We first import the dart:io library to use the stdin and stdout objects for user input and program output, respectively.

2. We prompt the user to enter the first number and store it as a double value in the num1 variable. We use the readLineSync() method to read the user's input from the command line and the double.parse() method to convert the user's input from a string to a double.

3. We do the same for the second number, storing the user's input as a double value in the num2 variable.

4. We calculate the average of the two numbers using the formula (num1 + num2) / 2 and store it as a double value in the avg variable.

5. We use the toStringAsFixed() method with an argument of 2 to format the avg variable with two decimal places, and use string interpolation to output the calculated average to the console in a user-friendly message.


# VOLUME AND SURFACE AREA OF A SPHERE

DESCRIPTION:

A program that prompts the user to enter a radius and then calculates the volume and surface area of a sphere. The formulas for volume and surface area are V = (4/3) * pi * r^3 and A = 4 * pi * r^2, respectively.

HOW IT WORKS:

1. We first import the dart:io library to use the stdin and stdout objects for user input and program output, respectively. We also import the dart:math library to use the pi constant and the pow() function for calculating powers.

2. We prompt the user to enter the radius of the sphere and store it as a double value in the radius variable. We use the readLineSync() method to read the user's input from the command line and the double.parse() method to convert the user's input from a string to a double.

3. We calculate the volume of the sphere using the formula (4 / 3) * pi * r^3 and store it as a double value in the volume variable.

4. We calculate the surface area of the sphere using the formula 4 * pi * r^2 and store it as a double value in the surfaceArea variable.

5. We use the toStringAsFixed() method with an argument of 2 to format the volume and surfaceArea variables with two decimal places, and use string interpolation to output the calculated volume and surface area to the console in user-friendly messages.


# BASE TO THE EXPONENT

DESCRIPTION:

A program that prompts the user to enter a base and an exponent and then calculates the result of raising the base to the exponent. For example, if the user enters 2 and 3, the program should calculate 2^3 = 8.

HOW IT WORKS:

1. We first import the dart:io library to use the stdin and stdout objects for user input and program output, respectively. We also import the dart:math library to use the pow() function for raising numbers to powers.

2. We prompt the user to enter the base and store it as a double value in the base variable. We use the readLineSync() method to read the user's input from the command line and the double.parse() method to convert the user's input from a string to a double.

3. We prompt the user to enter the exponent and store it as a double value in the exponent variable, using the same methods as for the base input.

4. We use the pow() function to raise the base to the exponent and store the result as a double value in the result variable.

5. We use string interpolation to output a user-friendly message that displays the base, exponent, and calculated result.


# CONVERT TEMPERATURE CELSIUS TO FAHRENHEIT

DESCRIPTION:

A program that prompts the user to enter a temperature in Celsius and then converts it to Fahrenheit. The formula for converting Celsius to Fahrenheit is F = (9/5) * C + 32.

HOW IT WORKS:

1. We first import the dart:io library to use the stdin and stdout objects for user input and program output, respectively.

2. We prompt the user to enter a temperature in Celsius and store it as a double value in the celsius variable. We use the readLineSync() method to read the user's input from the command line and the double.parse() method to convert the user's input from a string to a double.

3. We use the formula (9 / 5) * C + 32 to convert the temperature from Celsius to Fahrenheit and store the result as a double value in the fahrenheit variable.

4. We use string interpolation to output a user-friendly message that displays the original temperature in Celsius and the calculated temperature in Fahrenheit.


# PRIME NUMBER

DESCRIPTION:

A program that prompts the user to enter a positive integer and then determines whether it is a prime number. A prime number is a positive integer greater than 1 that has no positive integer divisors other than 1 and itself.

HOW IT WORKS:

1. We first import the dart:io library to use the stdin and stdout objects for user input and program output, respectively.

2. We prompt the user to enter a positive integer and store it as an int value in the number variable. We use the readLineSync() method to read the user's input from the command line and the int.parse() method to convert the user's input from a string to an int.

3. We initialize a bool variable isPrime to true, assuming that the number is prime until we find evidence to the contrary.

4. We check whether the number is less than or equal to 1. If it is, we know it is not prime and set isPrime to false.

5. If the number is greater than 1, we loop through all integers from 2 to number ~/ 2 (the integer division of number by 2) to check whether any of them divide number evenly (i.e., with a remainder of 0). If we find any such integer, we know that number is not prime and set isPrime to false. We then break out of the loop because we have found the evidence we need.

6. If isPrime is still true after the loop, we know that number is prime and output a message indicating so. Otherwise, we output a message indicating that number is not prime.
