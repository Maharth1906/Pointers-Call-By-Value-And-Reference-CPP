C++ Programs – Call by Value, Call by Pointer, and Call by Reference

Aim:-

To understand and implement Call by Value, Call by Pointer, and Call by Reference in C++.

Software Used:-

Mingw compiler
Visual Studio Code
Online C++ compiler

Program 1 – Swap Using Call by Value:-

Explanation & Theory:

In this program, the swap() function takes two integer parameters by value. The values are swapped inside the function, but the changes are not reflected in the main() function because the parameters are passed as copies of the original variables.

Algorithm:

Start
Define swap(int x, int y) to swap local copies of variables
In main(), declare two integers a and b
Call the swap() function with a and b
Display values inside the function and in main()
End

Program 2 – Swap Using Call by Pointer:-

Explanation & Theory:

In this program, the swap() function takes pointers to integers as parameters.
This allows the function to directly access and modify the memory locations of the original variables, so changes are reflected in main().

Algorithm:

Start
Define swap(int *x, int *y) to swap values at the addresses pointed to
In main(), declare two integers a and b
Call the swap() function with the addresses of a and b
Display values inside the function and in main()
End

Program 3 – Increment Using Call by Reference:-

Explanation & Theory:

In this program, the increment() function takes a reference parameter.
This allows the function to work directly with the original variable without using pointers,
making the syntax simpler while still modifying the actual variable in main().

Algorithm:

Start
Define increment(int &s) to increase salary by 5000
In main(), declare an integer sal with an initial value
Call increment() with sal as the argument
Display the salary inside the function and in main()
End

Conclusion:-

Call by Value: Works with copies of the variables, so original values remain unchanged.
Call by Pointer: Works with memory addresses, so changes affect the original variables.
Call by Reference: Works with an alias to the original variable, allowing direct modification without pointers.
