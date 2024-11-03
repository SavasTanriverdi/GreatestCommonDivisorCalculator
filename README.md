GreatestCommonDivisorCalculator

This project is a Java program designed to calculate the GCD (Greatest Common Divisor) of two numbers entered by the user. The GCD of two numbers is the largest number that divides both numbers without leaving a remainder. This program uses the Euclidean algorithm to compute the GCD efficiently.
Project Structure

    GreatestCommonDivisorCalculator.java: Contains the main method that prompts the user for input and calls calculateGCD to find the GCD of the two numbers.

Code Overview
Methods

    main Method
        Functionality: Prompts the user to enter two numbers and calls calculateGCD with these inputs.
        User Input: num1 and num2, which are the two integers entered by the user.
        Output: Displays the GCD of the two numbers.

    calculateGCD(int a, int b)
        Description: Calculates the GCD of two integers using the Euclidean algorithm.
        Parameters:
            int a - the first integer.
            int b - the second integer.
        Returns: int - the GCD of a and b.
        Logic:
            While b is not zero, set b to a % b and swap the values of a and b.
            When b reaches zero, a will hold the GCD.

Usage
Example run:

    Enter the first number: 48
    Enter the second number: 18
    The Greatest Common Divisor (GCD) of 48 and 18 is: 6

Key Concepts

    Greatest Common Divisor (GCD): The largest positive integer that divides both numbers without leaving a remainder.
    Euclidean Algorithm: An efficient method for finding the GCD of two numbers by repeatedly applying the modulo operation.

Author

This project is a basic Java example for calculating the GCD of two numbers using user input, designed for educational purposes.
