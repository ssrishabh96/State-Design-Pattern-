# State Design Pattern implemented in Java

In software engineering, the singleton pattern is a software design pattern that restricts the instantiation of a class to one "single" instance. This is useful when exactly one object is needed to coordinate actions across the system. The term comes from the mathematical concept of a singleton.

Critics consider the singleton to be an anti-pattern in that it is frequently used in scenarios where it is not beneficial, introduces unnecessary restrictions in situations where a sole instance of a class is not actually required, and introduces global state into an application.

## Overview
The singleton design pattern is one of the twenty-three well-known "Gang of Four" design patterns that describe how to solve recurring design problems to design flexible and reusable object-oriented software, that is, objects that are easier to implement, change, test, and reuse.

### The singleton design pattern solves problems like:

- How can it be ensured that a class has only one instance?
- How can the sole instance of a class be accessed easily?
- How can a class control its instantiation?
- How can the number of instances of a class be restricted?

### The singleton design pattern describes how to solve such problems:

- Hide the constructor of the class.
- Define a public static operation (getInstance()) that returns the sole instance of the class.
- The key idea in this pattern is to make the class itself responsible for controlling its instantiation (that it is instantiated only once).
- The hidden constructor (declared private) ensures that the class can never be instantiated from outside the class.
- The public static operation can be accessed easily by using the class name and operation name (Singleton.getInstance()).

Source: (Wikipedia)