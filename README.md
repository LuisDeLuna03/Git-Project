# GCD Calculator

## Purpose:
This Java program calculates the greatest common divisor (GCD) of two numbers using the BigInteger class. It provides a solution for finding the GCD of very large numbers which cannot be handled using primitive data types like int or long.

## Approach:
The program utilizes the Euclidean algorithm to find the GCD of two BigInteger numbers. This algorithm states that the GCD of two numbers remains the same if the larger number is replaced by its difference with the smaller number. This process is repeated until one of the numbers becomes zero, at which point the other number becomes the GCD.

## Assumptions:
- The program assumes that the input numbers can be both positive and negative. However, the GCD is always calculated as a positive number.
- The program handles very large numbers efficiently using the BigInteger class, but it does not handle non-integer inputs or invalid inputs.

## Special Instructions:
- Ensure that you have Java installed on your system to compile and run the program.
- No external libraries or dependencies are used in this program.

## Compilation and Running Instructions:
1. Open a terminal or command prompt.
2. Navigate to the directory containing the Java source code file (GCDCalculator.java).
3. Compile the program using the following command: javac GCDCalculator.java
4. After successful compilation, run the program using the following command: java GCDCalculator
5. Follow the on-screen instructions to enter the two numbers for which you want to find the GCD.
6. The program will output the GCD of the provided numbers.

## External Libraries or Dependencies:
This program does not require any external libraries or dependencies. It only uses the standard Java libraries.

Use this website https://readme.so/editor so that you can see the preview of this output 
