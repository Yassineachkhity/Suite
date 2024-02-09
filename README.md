# Suite
## Description
This C++ program calculates the number of iterations required to reach 0 starting from a given number following a specific set of rules. <br> The rules are as follows: <br>

If the current number is divisible by 3, add 4 to it. <br>
If the current number is divisible by 4, divide it by 2. <br>
If the current number is neither divisible by 3 nor by 4, subtract 1 from it. <br>

## Usage
Compile the program using a C++ compiler. <br>
Run the compiled executable. <br>
Follow the prompts to input the starting and ending numbers for the range of values to calculate. <br>
### How to Run
To compile the program, you can use a C++ compiler such as g++: <br>

## Copy code
g++ -o program_name program_file.cpp <br>
Replace program_name with the desired name for the executable and program_file.cpp with the name of the file containing the source code. <br>

### To run the compiled program:

bash
./program_name <br>
Follow the prompts on the screen to input the starting and ending numbers for the range of values to calculate. <br>

### Input Requirements
The starting number (debut) must be an integer greater than or equal to 1. <br>
The ending number (fin) must be an integer greater than or equal to the starting number. <br>
### Output
For each integer in the specified range, the program outputs the number and the number of iterations required to reach 0 following the specified rules. <br>

## Example
rust
Copy code
de (>= 1) ? 3 <br>
a (>= 3) ? 8 <br>
3 -> 7 <br>
4 -> 2 <br>
5 -> 5 <br>
6 -> 6 <br>
7 -> 7 <br>
8 -> 4 <br>
## Note
Ensure that the starting number is less than or equal to the ending number to avoid unexpected behavior. <br>
