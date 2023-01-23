# Gaussian Elimination

## AIM:
To write a program to find the solution of a matrix using Gaussian Elimination.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.Import the numpy module to use the built in function for calculations.
2.Assign in np.array
3.Using the np.linalg.solve(), we can find the solution
4.End the program and display the result using print statement.

## Program:
```
/*
Program to find the solution of a matrix using Gaussian Elimination.
Developed by: keerthana jayasri
RegisterNumber: 22006582
*/
```
import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)


## Output:
![gaussian elimination]()![Screenshot (20)](https://user-images.githubusercontent.com/121163440/213972098-076e7759-46e5-4242-a03a-0156e0c233d2.png)



## Result:
Thus the program to find the solution of a matrix using Gaussian Elimination is written and verified using python programming.

