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
import numpy as np

A = np.array([[1, -3],
              [3,  1]])

B = np.array([0, 10])

solution = np.linalg.solve(A, B)

print(solution)

## Output:
<img width="1292" height="882" alt="Screenshot 2025-08-21 102107" src="https://github.com/user-attachments/assets/42ac2aae-bec6-4a76-9fb0-948b953b0318" />



## Result: 
Thus the solutions for the linear equations are successfully solved using python program

