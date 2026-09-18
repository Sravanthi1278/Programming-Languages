# What is Java?<br>
Java is a high-level, object-oriented programming language developed by Sun Microsystems and now maintained by Oracle.<br>
Java is a popular and powerful programming language, created in 1995.
### . What is Programming?
Programming is the process of writing instructions for a computer to perform a specific task or solve a problem.<br>
## What is a Programming Language.
A programming language is a language used by programmers to write instructions that can be processed by a computer.<br>
## What is a Programmer?
A programmer is a person who writes, tests, debugs, and maintains computer programs using programming languages.
For example, a person who writes Java code is called a Java programmer.
### What does a programmer do?
A programmer generally:<br>

1.Understands the problem<br>
2.Designs a solution<br>
3.Writes code<br>
4.Compiles/runs the code<br>
5.Finds errors<br>
6.Fixes errors<br>
7.Tests the program<br>
8.Maintains and improves the program

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
Windows / Linux / macOS.<br>

## What is a Compiler?

Since you asked about Java compiler and interpreter earlier, let's connect it.<br>
A compiler is a software that translates source code written in a programming language into another form that can be executed by a computer or runtime environment.<br>

In Java, the compiler is:<br>
javac<br>
For example:<br>
javac Hello.java<br>
The compiler converts:<br>
Hello.java<br>
     ↓<br>
Java Compiler (javac)<br>
     ↓<br>
Hello.class<br>

The .class file contains bytecode.<br>

JDK vs JRE vs JVM<br>

### JVM

Java Virtual Machine

It runs Java bytecode.

.class file → JVM → Program runs<br>
Main job of JVM

## The JVM:
Loads bytecode<br>
Verifies bytecode<br>
Executes bytecode<br>
Uses the interpreter<br>
Uses JIT compilation for frequently executed code<br>
Manages memory

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


