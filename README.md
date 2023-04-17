# Java Practice
A place to staret learning Java basics

## Beginner Notes

* ___Sun Microsystems released Java in 1995.___ Slogan was "write once, run everywhere" due to the Java Virtual Machine which ensures the same Java code can be run on different operating systems.
* Java files have ___.java___ extenison.
* ```public static void main(String[] args) {}``` is the common signature for the ```main()``` method. The main method executes the task of the class.
* ```System``` is a built-in Java class that contains useful tools for our programs
* ```out``` is short for output
* ```println``` is short for print line, curcor moves to next line
* ```print``` leaves the cursor on the same line
* ```//``` for single line comment
* ```/* (comment) */``` for multi-line comment
* ```/**  */``` for Javadoc comments. Used to create documentation for APIs. Commonly written before the declaration of fields, methods, and classes
* ___Java is a class based language.___ Classes have a ```main``` method. Class names much match file names. File and class names are ___Pascal cased.___ Methods are ___camel cased.___
* ___Java is a compiled mprogramming language and is case sensitive.___
* ```javac``` terminal command to compile ```.java``` file. Produces a ```.class``` file if successful.
* ```java``` to run executable ```.class``` file.

### Code Example: HelloWorld
```
public class HelloWorld {
  public static void main(String[] args) {
    System.out.println("Hello World!");
  }
}
```
