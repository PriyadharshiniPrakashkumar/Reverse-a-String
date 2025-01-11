# Reverse String Using Pointers

This is a simple C++ program that reverses a given string using pointers. The program demonstrates the use of pointers to manipulate strings efficiently.

## How It Works

1. The program accepts a string input from the user.
2. It uses two pointers:
   - One pointing to the start of the string.
   - Another pointing to the end of the string.
3. Characters at these pointer positions are swapped until the pointers meet in the middle.

## Features
- Demonstrates string manipulation using pointers.
- Accepts strings with spaces using `cin.getline()`.

## Code Structure

- **`reverseString(char* str)`**: A function that reverses the given string in-place using pointers.
- **`main()`**: The main function where user input is handled, and the reversing function is called.

## Input Format
The program accepts a single line of input (up to 100 characters), which can include spaces.

## Output Format
The program outputs:
1. The original string entered by the user.
2. The reversed version of the string.

## Example

### Input:
```
Enter a string to reverse: Hello, World!
```

### Output:
```
Original string: Hello, World!
Reversed string: !dlroW ,olleH
```

## How to Compile and Run

1. Save the code to a file, for example, `reverse_string.cpp`.
2. Open a terminal or command prompt.
3. Navigate to the directory where the file is saved.
4. Compile the program using a C++ compiler like `g++`:
   ```
   g++ reverse_string.cpp -o reverse_string
   ```
5. Run the compiled program:
   ```
   ./reverse_string
   ```

## Dependencies
- A C++ compiler (e.g., GCC or Clang).

## Notes
- Ensure the input string does not exceed 99 characters to avoid buffer overflow.
- This program is intended for educational purposes to demonstrate pointer-based string manipulation.

