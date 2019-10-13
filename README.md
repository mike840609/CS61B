---
description: Berkeley  CS61B note
---

# Java Basic Program

## Basic Java 

### Java is an object oriented language with strict requirement

* every java file must contain a class declaration 
* all code lives inside a class\* , even helper functions, global constants, etc.
*  To run a Java program, you typically define a main method using  public static void main\(String \[\] args\){ }

### Java is statically typed!

* All variable, parameters, and methods must have a declared type.
* That type can never change.
* Expressions also have a type. 
* The compiler checks that all the types in your program are compatible before the program  
  * This is unlike a language like Python, where type checks are performed DURING execution. 
* Static Typing  one of the best features of Java. It gives us a number of important advantages over languages without static typing: 
  * Types are checked before the program is even run, allowing developers to catch type errors with ease.
  * If you write a program and distribute the compiled version, it is \(mostly\) guaranteed to be free of any type errors. This makes your code more reliable.
  * Every variable, parameter, and function has a declared type, making it easier for a programmer to understand and reason about code. 
  * Code is verbose
  * Code is less general. There is a way around this in Java\(generics\).



