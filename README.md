# Java ArrayIndexOutOfBoundsException Bug

This repository contains a simple Java program that demonstrates an `ArrayIndexOutOfBoundsException`. The bug arises from an off-by-one error in the loop condition when accessing array elements. The solution demonstrates how to fix the error to prevent the exception.

## Bug Description

The `bug.java` file contains code that attempts to access an array element beyond its valid index range. This leads to an `ArrayIndexOutOfBoundsException` during runtime.

## Solution

The `bugSolution.java` file presents the corrected code. The loop condition is modified to prevent accessing an index that is out of bounds.

## How to Run

1. Clone this repository.
2. Compile the Java files: `javac *.java`
3. Run the program: `java MyClass`
