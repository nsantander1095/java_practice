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
* ```javac``` terminal command to compile ```.java``` file, include file extension. Produces a ```.class``` file if successful.
* ```java``` to run executable ```.class``` file, do not include file extension when running.

### Code Example: HelloWorld
```
public class HelloWorld {
  public static void main(String[] args) {
    System.out.println("Hello World!");
  }
}
```
### Variables

* Eight primitive data types: int, double, boolean, char (surrounded by single quotes), byte, long, short, float. Also null, but we know about that.
* ___Literal___ - when code is used to to represent a fixed value.
* Strings are objects, not primitives. There are two ways to to create a ```String``` object:
  * using a ```String``` literal
    * ```String greeting = "Hello World!";```
  * calling the ```String``` class to create a new ```String``` object
    * ```String salutations = new String("Hello World!");```
* Escape characters:
  * ```\"``` allows you to use ```"``` in a string value
    * prints ```"Hello World"``` instead of ```Hello World!```
  * ```\\``` allows you to use backslashes in a string
    * prints ```this is a the backslash symbol: \``` as example
  * ```\n``` is still new line escape character
    * if used in the middle of a string, eg ```"Hello\nGoodbye"``` then Goodbye would be on the next line
* Compound assignment operators:
  * Addition - ```+=```
  * Subtraction - ```-=```
  * Multiplication - ```*=```
  * Division - ```/=```
  * Modulo - ```%=```
