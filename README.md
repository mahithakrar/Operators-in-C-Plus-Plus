# Operators in C++ and Conditional Statements

## 📌 Overview

This project demonstrates the use of **operators** and **conditional statements** in C++.  
Operators are symbols that perform operations on variables and values, while conditional statements allow the program to make decisions based on certain conditions.  
Understanding these concepts is essential for writing logical, efficient, and interactive programs.

---

## Theory

### 1. Operators in C++
In C++, operators are used to perform various operations on variables and values. They are grouped into several categories:

####  Arithmetic Operators
Used to perform basic mathematical operations:
- `+` Addition
- `-` Subtraction
- `*` Multiplication
- `/` Division
- `%` Modulus (remainder)

####  Relational (Comparison) Operators
Used to compare two values:
- `==` Equal to  
- `!=` Not equal to  
- `>` Greater than  
- `<` Less than  
- `>=` Greater than or equal to  
- `<=` Less than or equal to  

####  Logical Operators
Used to combine multiple conditions:
- `&&` Logical AND  
- `||` Logical OR  
- `!` Logical NOT  

####  Assignment Operators
Used to assign values to variables:
- `=` Assign  
- `+=`, `-=`, `*=`, `/=`, `%=` Compound assignments  

---

### 2. Conditional Statements in C++
Conditional statements control the flow of a program by evaluating whether expressions are `true` or `false`.

####  `if` Statement
Executes a block of code if a condition is true.

####  `if-else` Statement
Chooses between two blocks of code.

####  `else` Statement
Executes a block of code if a condition is not true.

---

## 💻 Example Programs

### **1. Grade Calculator**
This program:
- Takes marks of five subjects from the user
- Calculates the average
- Displays the corresponding grade using if-else conditions

**Key Concepts Used:**
- Arithmetic operations
- Average calculation
- Multiple if-else blocks
- Relational and logical operators

## Algorithm
1. **Start**
2. Declare five integer variables: `sub1`, `sub2`, `sub3`, `sub4`, `sub5` and one float variable `avg`.
3. Prompt the user to enter marks for all five subjects.
4. Read and store the marks.
5. Calculate the average:
`avg = (sub1 + sub2 + sub3 + sub4 + sub5) / 5`
6. Use conditional checks:
- If `80 < avg && avg < 90` → Grade = **O**
- Else if `70 < avg && avg < 80` → Grade = **A+**
- Else if `60 < avg && avg < 70` → Grade = **A**
- Else if `50 < avg && avg < 60` → Grade = **B**
- Else if `40 < avg && avg < 50` → Grade = **C**
- Else → **Fail**
7. Display the grade.
8. **End**

---

---

### **2. Number Sign Checker**
This program:
- Checks whether the entered number is positive, negative, or zero using conditional logic

**Key Concepts Used:**
- Basic condition checking
- if-else structure
- Use of comparison operators

## Algorithm
1. **Start**
2. Declare an integer variable `a`.
3. Prompt the user to **enter a number**.
4. Read the value into `a`.
5. If `a > 0`  
   → Display: "The given number is positive".
6. Else if `a < 0`  
   → Display: "The given number is negative".
7. Else  
   → Display: "Number is zero".
8. **End**

---

### **3. Quadrant Locator**
This program:
- Determines in which quadrant a point lies on the Cartesian plane based on its x and y coordinates
- Handles edge cases like origin or points on axes

**Key Concepts Used:**
- Compound conditions using `&&`
- Multiple `else if` branches
- Applying geometry concepts through logic

# Algorithm: Determine Quadrant or Axis of a Coordinate

## Step-by-Step Procedure

1. **Start**  
2. **Declare** two integer variables `x` and `y` for storing coordinates.  
3. **Prompt** the user to enter the first coordinate (`x`).  
4. **Read** the value of `x`.  
5. **Prompt** the user to enter the second coordinate (`y`).  
6. **Read** the value of `y`.  
7. **Check Conditions**:  
   - If `x > 0` **and** `y > 0`, display: *"The co-ordinates lie in the first quadrant"*.  
   - Else if `x < 0` **and** `y > 0`, display: *"The co-ordinates lie in the second quadrant"*.  
   - Else if `x < 0` **and** `y < 0`, display: *"The co-ordinates lie in the third quadrant"*.  
   - Else if `x > 0` **and** `y < 0`, display: *"The co-ordinates lie in the fourth quadrant"*.  
   - Else if `x != 0` **and** `y == 0`, display: *"The co-ordinates lie on the x-axis"*.  
   - Else if `x == 0` **and** `y != 0`, display: *"The co-ordinates lie on the y-axis"*.  
   - Else, display: *"The co-ordinates lie on the origin"*.  
8. **End**  

---

## 📖 Conclusion

- **Operators** are the foundation of logic and computation in C++.  
- **Conditional statements** enable decision-making and program flow control.  

From this project, you learn how to:
1. Use different types of operators
2. Evaluate expressions
3. Apply logic in conditional statements
4. Create interactive and responsive C++ applications

Mastering these concepts is essential for writing effective C++ programs, whether they are simple or complex.

---
