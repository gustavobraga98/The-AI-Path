---
title: Variables and Data Types (Notes)
has_children: true
parent: Java Programming Basics
grand_parent: Introduction
nav_order: 1
---

# Variables and Data Types

## Core Concepts:
1. Java is case sensitive.
That means that letter case matters. (A differs from a)
2. Semi-colon means end of statement.
3. String Concatenation: 

    If you have two different strings like the name and the last name of someone:
    ```java
    String Name;
    String LastName;
    Name = "Hamish"
    LastName = "Blake"
    ```
    you can concatenate them by using:
    ```java
    String FullName;
    FullName = Name+" "+LastName
    ```
    And the output will be: "Hamish Blake"
4. Declare and Initialize Variables:

    You can declare a variable and start it with some value, for example:
    ```java
    String Name = "Jake";
    ```

5. Variable Types:
    * Integer — Simple numbers, like 1, 2 and 5
    * String — Is a variable that can hold anything that's made up of characters.
    * Character — (Is a single Alphabetical letter, digit or even a symbol.)
    * Long — Stores 64 bits in integer form
    * double — Stores a decimal Long like 1.2, 4.9, 15.2

6. Casting:
    ```java
    double = current = 17;
    double rate = 1.5;
    double future = current*rate;
    System.out.println(future);
    ```
    That will result in 25.5, but we can cast the integer variable to get only the left part of the number.
    ```java
    int approx = (int) future;
    System.out.println(approx);
    ```
    And There we go, the print will be 25

7. Commenting:
    Just insert "//" for single line comments or /* Comment Here */ for multiple lines comments
## Summary of commands:
* System.out.println(); — Prints somethin in a newline
    * Example: System.out.println("Hello World") Prints on the screen "Hello World"
* int variable_name; — Creates a integer variable.
* variable(string).length(); — Returns the count of the characters of a string.
* variable(string).toUpperCase(); — Transforms the string in an all Uppercase sentence.
* variable(string).toLowerCase(); —Transforms the string in an all Lowercase sentence.

## Problem Set 1:
You can find the problem set here: [Problem Set 1](https://d17h27t6h515a5.cloudfront.net/topher/2016/July/57881edd_problem-set-1/problem-set-1.pdf)