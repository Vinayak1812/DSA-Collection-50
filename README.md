Q1 : What is an array? How is it stored in memory?
Ans : An array is a data structure that stores a collection of elements, all of the same type (e.g., integers, floating-point numbers, characters). It organizes data in contiguous memory locations, making it efficient to access and manipulate elements using their index.
Key Characteristics of an Array:
Fixed Size: Arrays have a predetermined number of elements (its size), which cannot change after declaration.
Index-Based: Each element in the array can be accessed by its index, starting from 0 for the first element.
Homogeneous Elements: All elements must be of the same data type.
How Is It Stored in Memory?
Contiguous Memory Locations: The elements of an array are stored in adjacent memory addresses.
Base Address: The address of the first element (index 0) serves as the base address. The subsequent elements are placed at offsets based on their size.
Address Calculation: The address of an element can be calculated using:
Address = Base Address+(Index×Size of Each Element)


Q2 : How do you find the largest element in an array?
Ans : Via Linear Search : O(n)
      Via Sorting  : O(n log n)
      via divide and conqure method (
      via build in function 

Q3 : Write a program to reverse an array.
Ans : double pointer 
