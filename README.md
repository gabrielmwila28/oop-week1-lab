# OOP Week 1 Lab

## Student

**Names:** Gabriel Mwila 2410234,
          Mwelwa Kondwani 2410395,
          Martin Muloshi 2410009,
          Joshua Mazaza 2410123,
          Innocent Kabwe 2410109

## Course

**Object-Oriented Programming (OOP)**

## Date

**18 August 2026**

## Lab Overview

This repository contains my Week 1 Object-Oriented Programming practical work.

The lab covered:

* Checking the Java Development Kit (JDK) and JVM setup
* Compiling and running Java programs
* Understanding procedural programming
* Demonstrating an `ArrayIndexOutOfBoundsException`
* Solving the problem using Object-Oriented Programming
* Creating and using a `Person` class
* Creating objects using constructors
* Using methods to display object information
* Using Git and GitHub to save and manage my work
* Using AI as a learning and debugging assistant

## Files

### `Hello.java`

A simple Java program used to test whether Java was installed and working correctly.

### `procedural.java`

Demonstrates the problem of storing related information in separate arrays for names and ages.

The program produces an `ArrayIndexOutOfBoundsException` when a new person is added without adding a corresponding age.

### `oop.java`

Demonstrates the Object-Oriented Programming solution using a `Person` class.

Each `Person` object contains:

* Name
* Age
* `printDetails()` method

## OOP Concepts Learned

### Class

A class is a blueprint used to create objects.

### Object

An object is an instance of a class containing its own data and behaviour.

### Constructor

A constructor initializes an object when it is created.

### Attributes

Attributes store information about an object, such as a person's name and age.

### Method

A method defines behaviour that an object can perform.

## How to Compile and Run

Compile the programs using:

```bash
javac Hello.java
javac procedural.java
javac oop.java
```

Run them using:

```bash
java Hello
java procedural
java oop
```

## Example OOP Output

```text
Ben is 10 years old
Mary is 6 years old
Leo is 97 years old
John is 25 years old
```

## Git Commands Practiced

```bash
git add .
git commit -m "Add Week 1 lab files"
git push
git pull
git checkout -b experiment
git checkout main
```

## Reflection

The practical demonstrated that related data should be grouped together in objects rather than stored separately in different arrays. Using a `Person` object keeps a person's name and age together and reduces the possibility of mismatched data.

Git was also used to keep versions of the project and provide a way to back up and share the work through GitHub.

## Conclusion

This Week 1 lab introduced the basic concepts of Java, Object-Oriented Programming, Git, GitHub, and responsible use of AI during software development.
