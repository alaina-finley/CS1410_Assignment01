# CS1410_Assignment01
Assignment 01 for CS 1410

Here are the instructions for Assignment 01 

"The goal of this assignment is to practice creating and compiling a program in Eclipse and to see how developers can break a problem into smaller pieces. You will do this by writing a small program that calculates the cost of a car trip.

To get started, follow these instructions:

If needed, install Java and then Eclipse on your machine. See instructions for this in the Course Technical Materials module in Canvas.
In your CS1410 project, make a package called a1.
Create a new class called DrivingCostCalculator. Warning, in CS1410, creating different package names or class names will result in a loss of points. This includes capitalization and typing errors.
In your main method, repeatedly call JOptionPane.showInputDialog with useful text prompts to the user to get the following information, in the order listed:
The driving distance, in miles
The vehicle's miles per gallon efficiency
The cost of gas in dollars per gallon
The cost of the trip is the distance * dollars per gallon / miles per gallon. This is easier to understand if it is broken into two parts:
The number of gallons used is the miles / miles per gallon
The cost is the number of gallons * dollars per gallon
Calculate the cost of the trip in two stages. First calculate the number of gallons used and store the result in a variable. Secondly, use that variable and the dollars per gallon to compute a final cost.
In order to improve the marketability of this program, make a text banner that displays before the trip cost result. The code for the text banner should be in a public static void method that looks like
public static void displayBanner()

add a block of statements to the above start to the method so that calling it displays something like:

     *****************************************
     *        Driving Cost Calculator        *
     *****************************************

     You may use your creativity for what is displayed.

Finish the program by calling the displayBanner method and then displaying the cost of the trip. The output must look like the following example, except the number result can change.
The cost of the trip is $5.1234
You do not have to worry about formatting the dollar amount to always have two decimal digits.
The top of the program file must have a comment with your name, the assignment (like "Assignment 1") and the course.
Testing
Run and test your program several times. Think of inputs that are easy for you to check. You do not need to worry about unusual inputs, such as numbers that are too large to store in a double variable or a zero MPG that causes division by zero in the math. As an example test, entering a driving distance of 100, a miles per gallon of 10, and a dollars per gallon of 2, the result is

       The cost of the trip is $20.0
  "
