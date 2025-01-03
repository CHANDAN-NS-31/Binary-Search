# Binary Search with Validation in C

## Description
This repository contains a C program that implements **Binary Search** with an additional functionality to validate whether the input array is sorted. Binary Search is an efficient algorithm used to find a target value in a sorted array. The program ensures the array is sorted before proceeding with the search.

---

## Features
- **Validation Function**: Checks if the input array is sorted.
- **Binary Search**: Efficiently finds the target element in the array.
- **Error Handling**: Prints appropriate messages if the array is unsorted or the target element is not found.

# Linear Search in C

## Description
This repository contains a C program implementing the **Linear Search** algorithm. The program uses a function to search for a target value in an array and returns all the indices where the target value is found.

---

## Features
- **Linear Search Implementation**: Efficiently searches for the target value in an array.
- **Multiple Occurrences**: Finds all matching indices if the target appears multiple times in the array.
- **Result Storage**: Uses an array to store the indices of matching elements.

---

## Code Overview

### **1. Linear Search**
The function `linearsearch` performs the following:
- Searches through each element of the array.
- If the target matches an element, the index is stored in the `result` array.
- The function also updates the `resultsize` variable to indicate how many times the target value was found.

### **2. Main Function**
- Prompts the user for input.
- Displays the indices where the target is found or a message if no match is found.

---

# Call by Value in C

## Description
This repository contains a C program demonstrating the concept of **Call by Value**. In this method, a copy of the actual argument is passed to the function, ensuring that changes made to the parameter inside the function do not affect the original variable in the calling function.

---

## Features
- Demonstrates the behavior of Call by Value using a simple example.
- Explains how values are copied and why the original variable remains unchanged.
- Includes a function `modifyValue` that modifies a local copy of the variable.

---

# Call by Reference in C

## Description
This repository contains a C program demonstrating the **Call by Reference** concept. In this approach, instead of passing a copy of the variable's value (as in Call by Value), the address (reference) of the variable is passed to the function, allowing the function to modify the original variable.

---

## Features
- **Call by Reference**: The program uses pointers to pass the memory address of variables to a function.
- **Modifies Original Values**: Changes made inside the function are reflected in the calling function.
- **Demonstrates Pointer Usage**: Shows how pointers are used to access and modify values in memory.

---

# Bubble Sort in C

## Description
This repository contains a C program implementing the **Bubble Sort** algorithm. Bubble Sort is a simple comparison-based sorting algorithm that repeatedly steps through the list, compares adjacent elements, and swaps them if they are in the wrong order.

---

## Features
- **Bubble Sort Implementation**: The program sorts an array of integers in ascending order.
- **Element Swapping**: If two adjacent elements are in the wrong order, they are swapped.
- **Efficiency**: The algorithm continues to compare adjacent elements until the array is sorted.

---

## Code Overview

### **1. Bubble Sort Logic**
The program performs the following:
- Iterates through the array multiple times, each time comparing adjacent elements.
- If an element is greater than the next one, it swaps them.
- The largest elements "bubble up" to the end of the array after each iteration.

### **2. Main Function**
- Accepts the array size and elements from the user.
- Calls the Bubble Sort algorithm to sort the array.
- Displays the sorted array.

---

# Pointer to Pointer in C

## Description
This repository contains a C program demonstrating the concept of **Pointer to Pointer** (also known as a double pointer). It uses multiple levels of indirection to modify and access the value of a variable through its pointers.

The program also explores various operations on pointers, such as pointer arithmetic and dereferencing pointers at different levels.

---

## Features
- **Pointer to Pointer**: Demonstrates the concept of multiple levels of indirection using pointers.
- **Pointer Arithmetic**: Performs pointer arithmetic to access elements in memory.
- **Dereferencing Pointers**: Accesses and modifies values at different levels using dereferencing operators (`*`).

---

## Code Overview

### **1. Pointer to Pointer Logic**
- The program uses:
  - `*p` (Pointer to `a`).
  - `**q` (Pointer to `p`).
  - `***r` (Pointer to `q`).
- It modifies the value of `a` at different levels of indirection.

### **2. Pointer Arithmetic**
- The program demonstrates accessing the next memory location using pointer arithmetic (`p+1`, `p+2`, etc.) and dereferencing them.

---

# Recursive Linear Search in C

## Description
This repository contains a C program implementing a **recursive linear search** algorithm. In this program, the search function uses recursion to find whether a target element exists in an array. The function iteratively checks each element until it finds the target or reaches the end of the array.

---

## Features
- **Recursive Linear Search**: The program searches for an element in the array using recursion instead of iteration.
- **Dynamic Input**: Takes input from the user for the array elements and the key to search for.
- **Element Found Check**: Returns a message indicating whether the key element is found in the array.

---

## Code Overview

### **1. Recursive Linear Search**
The program uses recursion in the `search` function to check if the element exists at each index of the array.

### **2. Main Function**
- The main function accepts the array size, elements, and the target element from the user.
- It calls the `search` function and displays whether the target element is found or not.

---
