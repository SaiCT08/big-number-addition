# Big Number Addition

A Java program that adds integers too large to fit in `int` or `long`.

## How it works

- Reads a list of numbers from a text file and stores each one as an array of digits (a jagged `byte[][]`)
- Adds the numbers column by column from right to left, carrying into the next column, the same way you would on paper
- Strips leading zeros and returns the sum as a string

## Files

- `BigNumberAdditionProject.java`: reads the input file and performs the addition
- `BigNumberAdditionRunnerClass.java`: runs the program on an input file and prints the result

## Built with

Java
