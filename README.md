# # Experiment 7: Study of Iterative Structures (Loops) in Python

## Author
- **Name:** Pushpak J  
- **PRN:** 25070123148  
- **Branch:** F.Y. E&TC (2025-29)  
- **Batch:** A1  
- **Subject:** Exploratory Data Analysis With Python  

---

## Aim
To study and implement different types of loops in Python, focusing on automating repetitive tasks and solving logic problems using iterative structures.

---

## Objectives
- Master the **while loop** for condition-based iteration  
- Use the **for loop** for range and sequence iteration  
- Apply **nested loops** for multi-dimensional problems  
- Learn **loop control statements** like `break` and `continue`  

---

## Theory and Concepts

### 1. While Loop
Executes a block repeatedly while a condition is true. Useful when the number of iterations is unknown.

### 2. For Loop
Iterates over sequences or ranges. Commonly used for fixed-length iterations.

### 3. Loop Control
- **break**: Exit loop early  
- **continue**: Skip current iteration  

### 4. Nested Loops
Loops inside loops, used for matrix operations, combinations, and pattern printing.

---

## Practical Implementation

### Matrix Multiplication
```python
# Triple nested loop for matrix multiplication
for i in range(row1):
    for j in range(col2):
        for k in range(col1):
            result[i][j] += matrix_A[i][k] * matrix_B[k][j]
Floyd’s Triangle
python
n = int(input("Layers: "))
a = 1
for i in range(n+1):
    for j in range(i):
        print(a, end=" ")
        a += 1
    print()
Prime Numbers in Range
python
for num in range(n, m+1):
    for i in range(2, num):
        if num % i == 0:
            break
    else:
        print(num, end=" ")
Diamond Pattern
python
n = 5
for i in range(n,0,-1):
    print(i*" ", (n-i)*"* ")
for i in range(n):
    print(i*" ", (n-i)*"* ")
2D Plane with Stars
python
n = 5
for i in range(n):
    print(i*" ", n*" * ")
Applications
Basic Counter: while loop

Palindrome Checker: while loop

Matrix Multiplication: nested for loops

Digit Combinations: triple nested loops

Armstrong Finder: for loop

Pattern Printing: for loops with spacing

Conclusion
Loops are fundamental in Python for handling repetitive tasks efficiently.
This experiment demonstrated simple counters, conditional skips, and complex nested structures like matrix multiplication and pattern generation, highlighting the versatility of iterative control structures.
