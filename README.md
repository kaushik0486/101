# 101# Problem: Reverse a String

You are given a string. Write a function to reverse the characters in the string.

## Example

Input: "hello"
Output: "olleh"

## How to Use

1. Clone this repository.
2. Open a terminal or command prompt.
3. Navigate to the repository's directory.
4. Compile and run the solution code (see below).

## Solution

The solution is implemented in the programming language [Python](https://www.python.org/). The `reverse_string` function takes a string as input and returns the reversed string.

### Usage

```python
def reverse_string(s):
    return s[::-1]

input_string = "hello"
reversed_string = reverse_string(input_string)
print(reversed_string)
