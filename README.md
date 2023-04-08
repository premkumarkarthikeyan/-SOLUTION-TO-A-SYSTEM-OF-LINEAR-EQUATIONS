# -SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS

## Aim:

To write a python program to find a solution to a system of linear equations.

## Equipment’s required:

1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm:

### Step 1:

Import the numpy module to use the built-in functions for calculation

### Step 2: 

Prepare the lists from each linear equations and assign in np.array()

### Step 3: 

Using the np.linalg.solve(), we can find the solutions.

### Step 4: 

End the program

## Program:

```
#Program to find the solution for the given linear equations.
#Developed by: PREM KUMAR K
#RegisterNumber: 2122230111
import numpy as np
A=np.array([[1,3],[2,5]])
B=np.array([5,-3])
result=np.linalg.solve(A,B)
print(result)
```
## Output:

![Screenshot 2023-03-29 100347](https://user-images.githubusercontent.com/119476243/228767110-f72fcfd7-04ec-4952-92fc-70e0cd39b4aa.png)

## Result: 

Thus the solutions for the linear equations are successfully solved using python program

