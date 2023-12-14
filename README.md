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
A=np.array([[1,-3],[3,1]])
B=np.array([0,10])
le=np.linalg.solve(A,B)
print(le)
```
## Output:
![image](https://github.com/Daniel-christal/-SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS/assets/145742847/187d1bfa-f358-4ca7-a07c-e6dc9eafb01e)

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

