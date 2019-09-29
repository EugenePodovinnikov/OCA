# OCA
Oracle Certified Associate Java SE 8 Programmer I (Exam 1Z0-808)

一些资料和准备过程。

- OCA Java SE 8 Programmer I Exam Guide (Exam 1Z0-808) - Kathy Sierra, Bert Bates - 427页。
- OCA Oracle Certified Associate Java SE 8 Programmer I STUDY GUIDE - Jeanne Boyarsky and Scott Selikoff - 435页。
- Core Java Volume I - Fundamentals Tenth Edition - Cay S. Horstmann - 1038 页，看不完。
- Oracle Certified OCA Java 8 1Z0-808 Mock Exams Practice Tests/Questions - 这个貌似收费软件模拟测试，发现这个可以购买，Enthuware Mock Exams ￥74.83 感觉可以接受。
- OCA Java SE 8 Programmer I (1Z0-808) Complete Video Course - PEARSON 的视频 Simon Roberts
- OCA Java SE 8 Programmer I Certification Guide - Mala Gupata - 706页。
- https://docs.oracle.com/javase/8/docs/api/ - JDK 1.8 API

就这些资料已经够了，主要是时间怎么安排。国庆去玩的话，剩得半个月准备，按道理也够通过了，但是要 100% 正确率是很难的。期间就不能准备面试之类的了，全身心投入的话。搞完 OCA，年内也趁热打铁搞完 OCP。然后 Java SE 11 版本的呢？暂时不考虑那么远。



### CONTENTS AT A GLANCE

1. Declarations and Access Control
2. Object Orientation
3. Assignments
4. Operators
5. Flow Control and Exceptions
6. Strings, Arrays, ArrayLists, Dates, and Lambdas

   A. About the Download

​       Index



Table of Contents
Cover Page
Title Page
Copyright Page
Contents
Acknowledgments
Preface
Introduction
1 Declarations and Access Control
    Java Refresher
    Features and Benefits of Java (OCA Objective 1.5)
    Identifiers and Keywords (OCA Objectives 1.2 and 2.1)
        Legal Identifiers
        Oracle’s Java Code Conventions
        Define Classes (OCA Objectives 1.2, 1.3, 1.4, 6.4, and 7.5)
            Source File Declaration Rules
            Using the javac and java Commands
            Using public static void main(String[ ] args)
            Import Statements and the Java API
            Static Import Statements
            Class Declarations and Modifiers
        Exercise 1-1: Creating an Abstract Superclass and Concrete Subclass
        Use Interfaces (OCA Objective 7.5)
            Declaring an Interface
            Declaring Interface Constants
            Declaring default Interface Methods
            Declaring static Interface Methods
        Declare Class Members (OCA Objectives 2.1, 2.2, 2.3, 4.1, 4.2, 6.2, 6.3, and 6.4)
            Access Modifiers
            Nonaccess Member Modifiers
            Constructor Declarations
            Variable Declarations
        Declare and Use enums (OCA Objective 1.2)
            Declaring enums
        Certification Summary
        Two-Minute Drill
        Q&A Self Test
        Self Test Answers
2 Object Orientation
    Encapsulation (OCA Objectives 6.1 and 6.5)
    Inheritance and Polymorphism (OCA Objectives 7.1 and 7.2)
        The Evolution of Inheritance
        IS-A and HAS-A Relationships
    Polymorphism (OCA Objective 7.2)
    Overriding/Overloading (OCA Objectives 6.1 and 7.2)
        Overridden Methods
        Overloaded Methods
    Casting (OCA Objectives 2.2 and 7.3)
    Implementing an Interface (OCA Objective 7.5)
        Java 8—Now with Multiple Inheritance!
    Legal Return Types (OCA Objectives 2.2 and 6.1)
        Return Type Declarations
        Returning a Value
    Constructors and Instantiation (OCA Objectives 6.3 and 7.4)
        Constructor Basics
        Constructor Chaining
        Rules for Constructors
        Determine Whether a Default Constructor Will Be Created
        Overloaded Constructors
    Initialization Blocks (OCA Objectives 1.2 and 6.3-ish)
    Statics (OCA Objective 6.2)
        Static Variables and Methods
    Certification Summary
    Two-Minute Drill
    Q&A Self Test
    Self Test Answers
3 Assignments
    Stack and Heap—Quick Review
    Literals, Assignments, and Variables (OCA Objectives 2.1, 2.2, and 2.3)
        Literal Values for All Primitive Types
        Assignment Operators
        Exercise 3-1: Casting Primitives
    Scope (OCA Objective 1.1)
        Variable Scope
    Variable Initialization (OCA Objectives 2.1, 4.1, and 4.2)
        Using a Variable or Array Element That Is Uninitialized and Unassigned
        Local (Stack, Automatic) Primitives and Objects
    Passing Variables into Methods (OCA Objective 6.6)
        Passing Object Reference Variables
        Does Java Use Pass-By-Value Semantics?
        Passing Primitive Variables
    Garbage Collection (OCA Objective 2.4)
        Overview of Memory Management and Garbage Collection
        Overview of Java’s Garbage Collector
        Writing Code That Explicitly Makes Objects Eligible for Collection
        Exercise 3-2: Garbage Collection Experiment
    Certification Summary
    Two-Minute Drill
    Q&A Self Test
    Self Test Answers
4 Operators
    Java Operators (OCA Objectives 3.1, 3.2, and 3.3)
        Assignment Operators
        Relational Operators
        instanceof Comparison
        Arithmetic Operators
        Conditional Operator
        Logical Operators
        Operator Precedence
    Certification Summary
    Two-Minute Drill
    Q&A Self Test
    Self Test Answers
5 Flow Control and Exceptions
    Using if and switch Statements (OCA Objectives 3.3 and 3.4)
        if-else Branching
        switch Statements
        Exercise 5-1: Creating a switch-case Statement
    Creating Loops Constructs (OCA Objectives 5.1, 5.2, 5.3, 5.4, and 5.5)
        Using while Loops
        Using do Loops
        Using for Loops
        Using break and continue
        Unlabeled Statements
        Labeled Statements
        Exercise 5-2: Creating a Labeled while Loop
    Handling Exceptions (OCA Objectives 8.1, 8.2, 8.3, 8.4, and 8.5)
        Catching an Exception Using try and catch
        Using finally
        Propagating Uncaught Exceptions
        Exercise 5-3: Propagating and Catching an Exception
        Defining Exceptions
        Exception Hierarchy
        Handling an Entire Class Hierarchy of Exceptions
        Exception Matching
        Exception Declaration and the Public Interface
        Exercise 5-4: Creating an Exception
        Rethrowing the Same Exception
    Common Exceptions and Errors (OCA Objective 8.5)
        Where Exceptions Come From
        JVM-Thrown Exceptions
        Programmatically Thrown Exceptions
        A Summary of the Exam’s Exceptions and Errors
    Certification Summary
    Two-Minute Drill
    Q&A Self Test
    Self Test Answers
6 Strings, Arrays, ArrayLists, Dates, and Lambdas
    Using String and StringBuilder (OCA Objectives 9.2 and 9.1)
        The String Class
        Important Facts About Strings and Memory
        Important Methods in the String Class
        The StringBuilder Class
        Important Methods in the StringBuilder Class
    Working with Calendar Data (OCA Objective 9.3)
        Immutability
        Factory Classes
        Using and Manipulating Dates and Times
        Formatting Dates and Times
    Using Arrays (OCA Objectives 4.1 and 4.2)
        Declaring an Array
        Constructing an Array
        Initializing an Array
    Using ArrayLists and Wrappers (OCA Objectives 9.4 and 2.5)
        When to Use ArrayLists
        ArrayList Methods in Action
        Important Methods in the ArrayList Class
        Autoboxing with ArrayLists
        The Java 7 “Diamond” Syntax
    Advanced Encapsulation (OCA Objective 6.5)
        Encapsulation for Reference Variables
    Using Simple Lambdas (OCA Objective 9.5)
    Certification Summary
    Two-Minute Drill
    Q&A Self Test
    Self Test Answers
A About the Download
    System Requirements
    Downloading from McGraw-Hill Professional’s Media Center
        Installing the Practice Exam Software
        Running the Practice Exam Software
        Practice Exam Software Features
        Removing Installation
        Help
Technical Support
    Windows 8 Troubleshooting
    McGraw-Hill Education Content Support
Index



## OCA Objectives

#### Java Basics 

- Define the scope of variables 
- Define the structure of a Java class
- Create executable Java applications with a main method; run a Java program from the command line; produce console output
- Import other Java packages to make them accessible in your code
- Compare and contrast the features and components of Java such as: platform independence, object orientation, encapsulation, etc.

#### Using Operators and Decision Constructs 

- Use Java operators; use parentheses to override operator precedence
- Test equality between Strings and other objects using == and equals ()
- Create if and if/else and ternary constructs 
- Use a switch statement 

#### Using Loop Constructs 

- Create and use while loops
- Create and use for loops including the enhanced for loop
- Create and use do/while loops
- Compare loop constructs
- Use break and continue  

#### Working with Inheritance 

- Describe inheritance and its benefits
- Develop code that makes use of polymorphism; develop code that overrides methods;  differentiate between the type of a reference and the type of an object
- Determine when casting is necessary
- Use super and this to access objects and constructors
- Use abstract classes and interfaces

#### Working with Selected classes from the Java API 

- Manipulate data using the StringBuilder class and its methods
- Create and manipulate Strings
- Create and manipulate calendar data using classes from java.time.LocalDateTime,  java.time.LocalDate, java.time.LocalTime, java.time.format.DateTimeFormatter, java.time.Period
- Declare and use an ArrayList of a given type 
- Write a simple Lambda expression that consumes a Lambda Predicate expression

#### Working With Java Data Types 

- Declare and initialize variables (including casting of primitive data types)
- Differentiate between object reference variables and primitive variables
- Know how to read or write to object fields
- Explain an Object's Lifecycle (creation, "dereference by reassignment" and garbage collection)
- Develop code that uses wrapper classes such as Boolean, Double, and Integer  

#### Creating and Using Arrays 

- Declare, instantiate, initialize and use a one-dimensional array
- Declare, instantiate, initialize and use multi-dimensional arrays

#### Working with Methods and Encapsulation 

- Create methods with arguments and return values; including overloaded methods
- Apply the static keyword to methods and fields  
- Create and overload constructors; differentiate between default and user defined constructors
- Apply access modifiers
- Apply encapsulation principles to a class
- Determine the effect upon object references and primitive values when they are passed  into methods that change the values

#### Handling Exceptions 

- Differentiate among checked exceptions, unchecked exceptions, and Errors
- Create a try-catch block and determine how exceptions alter normal program flow
- Describe the advantages of Exception handling 
- Create and invoke a method that throws an exception
- Recognize common exception classes (such as NullPointerException, ArithmeticException, ArrayIndexOutOfBoundsException, ClassCastException)

#### Assume the following:

- **Missing package and import statements:** If sample code do not include package or import statements, and the question does not explicitly refer to these missing statements, then assume that all sample code is in the same package, or import statements exist to support them.

- No file or directory path names for classes:

   If a question does not state the file names or directory locations of classes, then assume one of the following, whichever will enable the code to compile and run:

  - All classes are in one file
  - Each class is contained in a separate file, and all files are in one directory

- **Unintended line breaks:** Sample code might have unintended line breaks. If you see a line of code that looks like it has wrapped, and this creates a situation where the wrapping is significant (for example, a quoted String literal has wrapped), assume that the wrapping is an extension of the same line, and the line does not contain a hard carriage return that would cause a compilation failure.

- **Code fragments:** A code fragment is a small section of source code that is presented without its context. Assume that all necessary supporting code exists and that the supporting environment fully supports the correct compilation and execution of the code shown and its omitted environment.

- **Descriptive comments:** Take descriptive comments, such as "setter and getters go here," at face value. Assume that correct code exists, compiles, and runs successfully to create the described effect.