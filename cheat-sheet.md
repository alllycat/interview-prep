# Interview Prep

Prepping for interviews suck, so I'm working on a summary resource to help you. This sheet is only a summary and does not cover everything in depth, however, it does reference links to more in-depth explanations.

# Table of Contents
* [link to content] (to be updated)
* [link to content]
* [link to content]

# Object Oriented Programming (OOP)

**Definition:** a programming language model organized around objects rather than "actions" and data rather than logic. Historically, a program has been viewed as a logical procedure that takes input data, processes it, and produces output data.

###Basic OO Terms

**Abstraction**: The process of separating ideas from specific instances of those ideas at work.

**Polymorphism**: The provision of a single interface to entities of different types. Subtyping.

**Inheritance**: When an object or class is based on another object or class, using the same implem­entation; it is a mechanism for code reuse. The relationships of objects or classes through inheri­tance give rise to a hierarchy.
* a subclass borrows attributes and methods from another class, namely a superclass.
* **Multiple inheritance** refers to the ability of a class to inherit attributes and methods from more than one superclass.

**Encapsulation**: Enclosing objects in a common interface in a way that makes them interc­han­geable, and guards their states from invalid changes
* A mechanism to restrict access to some of the object’s components

**Objects**: An object can be anything in the world with attributes and behaviours that can be written into a program.
* **Instantiation** is an act of creating an object from a class.
* **Initialization** sets the default values for an object.

**Classes**: A class refers to a group of common objects with same attributes and methods.
* An **instance** is the resulting object created from instantiating an object from a class.
* A **method** (or function) defines a particular behaviour of a class.
* **Constructor** is a method that creates an object from a class
* **Destructor Method** deletes the object and frees up memory that the object once occupied
* **Subclass** (a.k.a child class): A subclass borrows attributes and methods from the superclass.
* **Superclass** (a.k.a parent class): A superclass lends attributes and methods to subclass
* **Abstract class**: An abstract class cannot create instances of itself.

**Interface:** An interface is a set of related methods which are not suitable to be included in any classes.

**Method overloading:** Method overloading is the ability to create several methods with the same name that has different input and output. For example, method called “size” in Ruby performs differently for a string (returns length of the string) and an int value (returns the number of bytes occupied by the integer).

**Method overriding** is the ability of a subclass to replace a method that is already provided by one of its superclasses with a more specific implementation.

# Basic Data Structures

###1. Array

**Definition:** Stores data elements based on a sequential index, most commonly 0 based
* Based on tuples from set theory.
* They are one of the oldest, most commonly used data structures

**Pros:** Optimal for indexing

**Cons:** Bad at searching, inserting and deleting (except for the end)

#####Types of Arrays:

* **Linear Arrays** (one dimensional arrays) are the most basic.
  * Are static in size, meaning that they are declared with a fixed size.
* **Dynamic arrays** are like one dimensional arrays, but have reserved space for additional elements.
If a dynamic array is full, it copies it's contents to a larger array.
* **Two dimensional arrays** have x and y indices like a grid or nested arrays. It is a multidimensional array with two dimensions.
* **Multidimensional arrays** are arrays composed of elements that are arrays themselves. These can be extended to have as many dimensions as needed. 
  * (https://msdn.microsoft.com/en-us/library/2yd9wwz4.aspx) 
* **Jagged arrays** are multidimensional arrays composed of arrays that may vary in length
  * (https://msdn.microsoft.com/en-us/library/2s05feca.aspx?f=255&MSPPError=-2147217396)

#####Big O efficiency:

* **Indexing**: Linear array: O(1), Dynamic array: O(1)
* **Search**: Linear array: O(n), Dynamic array: O(n)
* **Optimized Search (Binary Search)**: Linear array: O(log n), Dynamic array: O(log n)
* **Insertion**: Linear array: O(n), Dynamic array: O(n)
  * *Note*: You cannot add more space at the end of a linear array, but you can insert a new element provided there is sufficient unused space within the existing array. To do so would require shifting every element from the desired insertion position to the last used position in the array by one towards the end. This would give a Big O complexity of O(n)

# Sorting Basics

###1. Merge Sort

**Definition:** A comparison based sorting algorithm
* Divides entire dataset into groups of at most two.
* Compares each number one at a time, moving the smallest number to left of the pair.
* Once all pairs sorted it then compares left most elements of the two leftmost pairs creating a sorted group of four with the smallest numbers on the left and the largest ones on the right.
* This process is repeated until there is only one set.


*This is one of the most basic sorting algorithms.
*Know that it divides all the data into as small possible sets then compares them.

#####Big O efficiency:

* Best Case Merge Sort: O(n)
* Average Case Merge Sort: O(n log n)
* Worst Case Merge Sort: O(n log n)

# Types of Algorithms

# Functional vs Iterative Programming


