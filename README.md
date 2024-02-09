# Suite
Description
This C++ program calculates the number of iterations required to reach 0 starting from a given number following a specific set of rules. The rules are as follows:

If the current number is divisible by 3, add 4 to it.
If the current number is divisible by 4, divide it by 2.
If the current number is neither divisible by 3 nor by 4, subtract 1 from it.

Usage
Compile the program using a C++ compiler.
Run the compiled executable.
Follow the prompts to input the starting and ending numbers for the range of values to calculate.
How to Run
To compile the program, you can use a C++ compiler such as g++:

Copy code
g++ -o program_name program_file.cpp
Replace program_name with the desired name for the executable and program_file.cpp with the name of the file containing the source code.

To run the compiled program:

bash
Copy code
./program_name
Follow the prompts on the screen to input the starting and ending numbers for the range of values to calculate.

Input Requirements
The starting number (debut) must be an integer greater than or equal to 1.
The ending number (fin) must be an integer greater than or equal to the starting number.
Output
For each integer in the specified range, the program outputs the number and the number of iterations required to reach 0 following the specified rules.

Example
rust
Copy code
de (>= 1) ? 3
a (>= 3) ? 8
3 -> 7
4 -> 2
5 -> 5
6 -> 6
7 -> 7
8 -> 4
Note
Ensure that the starting number is less than or equal to the ending number to avoid unexpected behavior.
