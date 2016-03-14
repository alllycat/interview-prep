# Interview Prep

Prepping for interviews suck, so I'm working on a resource to help others prep for them.

# Table of Contents
* [link to content] (to be updated)
* [link to content]
* [link to content]

# Object Oriented Programming

# Data Structures

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


