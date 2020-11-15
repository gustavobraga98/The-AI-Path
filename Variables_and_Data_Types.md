---
title: Variables and Data Types (Notes)
has_children: true
parent: Java Programming Basics
grandparent: Introduction
nav_order: 1
---

# Variables and Data Types

## Core Concepts:
1. Java is case sensitive.
That means that letter case matters. (A differs from a)
2. Semi-colon means end of statement.
3. String Variables: Is a variable that can hold anything that's made up of characters.
4. Characters: Is a single Alphabetical letter, digit or even a symbol.
5. String Concatenation: 

    If you have two different strings like the name and the last name of someone:
    '''java
    String Name;
    String LastName;
    Name = "Hamish"
    LastName = "Blake"
    '''
    you can concatenate them by using:
    '''java
    String FullName;
    FullName = Name+" "+LastName
    '''
    And the output will be: "Hamish Blake"

## Summary of commands:
* System.out.println(); — Prints somethin in a newline
    * Example: System.out.println("Hello World") Prints on the screen "Hello World"
* int variable_name; — Creates a integer variable.
* variable(string).length(); — Returns the count of the characters of a string.
* variable(string).toUpperCase(); — Transforms the string in an all Uppercase sentence.
* variable(string).toLowerCase(); —Transforms the string in an all Lowercase sentence.