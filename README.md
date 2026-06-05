# -SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS

~~~
Name: Hari Prasath M
Register No: 212225100015
~~~

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

Write a program to find a solution to a system of linear equations x+3y=5, 2x+5y=-3

Write a program to find a solution to a system of linear equations
5x-3y-10z=-9,
2x+2y-3z=4,
-3x-y+5z=-1
~~~
import os 
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np 
matrixA = np.array([[5, -3, -10],
                    [2, 2, -3],
                    [-3, -1, 5]])
constants=np.array([-9,4,-1])
result=np.linalg.solve(matrixA,constants)
print(result)
~~~

## Output:

<img width="741" height="172" alt="1" src="https://github.com/user-attachments/assets/2d72911e-6224-42c5-8ad2-64285b132139" />

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

