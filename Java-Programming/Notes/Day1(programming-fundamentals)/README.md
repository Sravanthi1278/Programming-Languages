# What is Java?<br>
Java is a high-level, object-oriented programming language developed by Sun Microsystems and now maintained by Oracle.<br>
Java is a popular and powerful programming language, created in 1995.

### Java is widely used for:

Backend development Web applications Android development Enterprise applications Banking applications Desktop applications

## 2 . Why Java?

One major reason Java is popular is: Write Once, Run Anywhere Java code is compiled into bytecode, which can run on different operating systems using a JVM.

### For example:

Java Code <br>
  ↓
Compiler<br>
  ↓ 
Bytecode<br>
  ↓ 
JVM<br> 
  ↓ 
Windows / Linux / macOS.

JDK vs JRE vs JVM

### JVM

Java Virtual Machine

It runs Java bytecode.

.class file → JVM → Program runs

### JRE

Java Runtime Environment
It provides the environment required to run Java programs.
JRE = JVM + Runtime Libraries

### JDK Java Development Kit
It is used to develop and run Java programs. JDK = JRE + Development Tools

Remember: 
JDK 
 ↓ 
JRE 
 ↓ 
JVM

Easy example Think of a car:
JDK = complete workshop + tools JRE = environment needed to use the car JVM = engine that actually runs the program
Your First Java Program Create a file called: Main.java
Write: public class Main { public static void main(String[] args) { System.out.println("Hello World"); } }

Output: Hello World

Understand Every Line
Line 1 public class Main { #This creates a class called Main. For now, remember: Java programs are organized using classes.
Line 2 public static void main(String[] args) { This is the main method. Java starts execution from the main() method. Don't try to memorize every word today. We'll break down:
public static void main String[] args
Line 3

System.out.println("Hello World");
This prints text on the screen.

### Example:
System.out.println("My name is Sravanthi");
System.out.println("I am learning Java");

Output: My name is Sravanthi 
I am learning Java

## print() vs println()
### println 
System.out.println("Hello");
System.out.println("Java");
Output: Hello Java

### print
System.out.print("Hello ");
System.out.print("Java");
Output: Hello Java

The difference is simple: println() moves to the next line. print() stays on the same line.

# Comments
Comments are notes for humans. Java doesn't execute them.
## Single-line comment
// This is a comment
System.out.println("Hello");

## Multi-line comment 
/* This is a multi-line comment */
System.out.println("Hello");


