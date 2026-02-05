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
import numpy as np

# Coefficient matrix
A = np.array([[5, -3, -10],[2,  2,  -3],[-3, -1,  5]])

# Constant matrix
B = np.array([-9, 4, -1])

# Solving the system
solution = np.linalg.solve(A, B)

print(solution)
```
## Output:
<img width="911" height="286" alt="screenshot-1770261731612 mfaigence 1" src="https://github.com/user-attachments/assets/a953a378-700b-43b0-b87b-4e3f7dd1a6dd" />

## Result: 
Thus the solutions for the linear equations are successfully solved using python program


