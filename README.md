# The Pattern of the Stars

A simple program to print a right-angled triangle pattern of stars based on a user-provided integer.

## 📝 Description

This Python program prompts the user to enter a single positive integer, n. Based on this number, it generates and prints a pattern of stars (*) forming a triangle with n rows. The first row has one star, the second has two, and so on, up to the n-th row which has n stars.

The core mathematical principle is the factorial, where the total is the result of n! (n being the number of times "RUN" was printed).

## 🎯 Problem Statement

**Input:** 
- A single integer (n).

**Output:** 
- A triangle pattern of stars if n is a positive integer.
- "NoPattern" if n is zero or a negative number.

**Rules:**
- The input number n must be a positive integer (greater than 0) for the pattern to be printed.
- If the input is 0 or a negative number, the program should not print a pattern and instead output a specific message.

## 💡 Examples

### Example 1 (n = 3)
```
Input:
3

Output:
*
**
***
```
Explanation: All inputs are valid. The average of (80 + 85 + 60) / 3 is 75.0.

### Example 2 (n = 5)
```
Input:
5

Output:
*
**
***
****
*****
```
Explanation: The third score, -3, is invalid. The program stops immediately.

### Example 3 (n = 0)
```
Input:
0

Output:
NoPattern
```
Explanation: The input is not a positive integer, so no pattern is generated.

### Example 4 (n = -1)
```
Input:
-1

Output:
NoPattern
```
Explanation: The input is a negative number, so no pattern is generated.


## 🚀 How to Use

1. Clone this repository
```bash
git clone https://github.com/adiaryaz/The-Pattern-of-the-Stars.git
cd calculate-circle-area
```

2. Run the program (assuming the file is main.py):
```bash
python main.py
```

3. Enter a positive integer when prompted to see the star pattern.
