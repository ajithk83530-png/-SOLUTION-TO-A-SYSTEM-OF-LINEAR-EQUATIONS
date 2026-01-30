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
```python
#Program to find the solution for the given linear equations.
#Developed by:Ajithkumar J 
#RegisterNumber:25008620
import numpy as np
A=np.array([[1,-3],[3,1]])
B=np.array([0,10])
c=np.linalg.solve(A,B)
print(c)
```

## Output:

<img width="749" height="745" alt="{F24C456A-0537-4976-A9B1-229AFAC010F5}" src="https://github.com/user-attachments/assets/fe8dcc4c-1676-453b-a7c2-5b02054ed547" />


## Result: 
Thus the solutions for the linear equations are successfully solved using python program

