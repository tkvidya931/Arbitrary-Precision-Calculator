# Arbitrary-Precision-Calculator(APC)

The Arbitrary Precision Calculator (APC) is a C-based application designed to perform arithmetic operations on very large integers that exceed the storage capacity of standard data types. The project uses doubly linked lists to represent numbers, where each digit is stored in a separate node, enabling efficient handling of integers of arbitrary size.

The calculator supports fundamental arithmetic operations including:

    Addition
    
    Subtraction
    
    Multiplication
    
    Division

Each operation is implemented using traditional arithmetic algorithms adapted for linked list representation.

Features:

    Handles integers of unlimited size
   Supports positive and negative numbers
   Performs arithmetic using doubly linked lists
   Dynamic memory allocation for efficient storage
   Proper carry and borrow handling
   Zero handling and result validation
   Modular and structured C implementation
   
Working Principle:


   Addition & Subtraction
   
        Digits are processed node by node from least significant digit to most significant digit while handling carries and borrows appropriately.

    Multiplication
    
         Implements the traditional schoolbook multiplication method with shifting of intermediate partial products.  

    Division
    
          Division is performed using repeated subtraction while tracking quotient generation.

Technologies Used:->

     C Programming Language
     
     Doubly Linked Lists
     
     Dynamic Memory Allocation
     
     Pointers and Structures
     
     Modular Programming
    
Concepts Demonstrated:

   This project helps in understanding:

           Linked list traversal
           
           Large number arithmetic
           
           Memory management in C
           
           Data structure implementation
           
           Algorithm design for mathematical operations
           
Applications:

          Cryptography
          
          Scientific Computing
          
          High-Precision Mathematical Computation
          
          Algorithm Development

Conclusion:

The APC project demonstrates how data structures can overcome the limitations of standard data types. It provides practical experience in implementing arithmetic logic using linked lists while strengthening concepts of modular programming and dynamic memory management.
