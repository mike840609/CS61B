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
* Curly braces are very important in Java 
  * if for statement without braces, it will work only next line.
  * Visualizer\([https://cscircles.cemc.uwaterloo.ca/java\_visualize/\#code=public+class+PrintAbsoluteValue+%7B%0A+++public+static+void+main\(String%5B%5D+args\)+%7B%0A++++++int+x+%3D+5%3B%0A++++++%0A++++++if+\(x+%3C+0\)+%0A++++++++System.out.println\(%22I+should+negate+X%22\)%3B%0A++++++++x+%3D+-x%3B%0A++++++%0A++++++System.out.println\(x\)%3B%0A+++%7D%0A%7D&mode=edit](https://cscircles.cemc.uwaterloo.ca/java_visualize/#code=public+class+PrintAbsoluteValue+%7B%0A+++public+static+void+main%28String%5B%5D+args%29+%7B%0A++++++int+x+%3D+5%3B%0A++++++%0A++++++if+%28x+%3C+0%29+%0A++++++++System.out.println%28%22I+should+negate+X%22%29%3B%0A++++++++x+%3D+-x%3B%0A++++++%0A++++++System.out.println%28x%29%3B%0A+++%7D%0A%7D&mode=edit)\)

```java
public class PrintAbsoluteValue {
   public static void main(String[] args) {
      int x = 5;      
      if (x < 0) 
        System.out.println("I should negate X");
        x = -x;      
      System.out.println(x);
   }
}
```





