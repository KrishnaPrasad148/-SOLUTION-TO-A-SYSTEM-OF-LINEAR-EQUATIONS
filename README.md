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

#Developed by: S.Krishna Prasad
#RegisterNumber: 212223230108
```
```
import numpy as np
a = np.array([[1,-3],[3,1]])
b = np.array([0,10])
c = np.linalg.solve(a,b)
print(c)
```

## Output:
![image](https://github.com/KrishnaPrasad148/-SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS/assets/147332763/a2e7c445-c480-468a-b744-522f1da76183)

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

