# Norm of a matrix

## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.

## Equipment’s required :

1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm:
	1. Get the input matrix using np.array()   
    2. Find the 2-norm of the matrix using np.linalg.norm()
	3. Print the norm of the matrix in two decimal places.

## Program:

### 1-Norm of a Matrix :-

```
# program to find the 1-norm of a matrix
# Developed by : Rajalakshmi R
# reg no : 212223110037

import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,1)
print("{:.2f}".format(norm))
```

### 2-Norm of a Matrix :-

```
# Program to find 2-norm of a matrix.
# Developed by: Rajalakshmi R
# RegisterNumber: 212223110037

import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,2)
print("{:.2f}".format(norm))
```

### Infinity Norm of a Matrix :-

```
# Program to find infinity norm of a matrix.
# Developed by: Rajalakshmi R
# RegisterNumber: 212223110037

import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,np.inf)
print("{:.2f}".format(norm))
```

## Output:

### 1-Norm of a Matrix
![image](https://github.com/Raji1009/Norm-of-a-matrix/assets/89059861/87f299b7-7129-4dcc-a21a-1d00c2ed55e0)


### 2-Norm of a Matrix
![image](https://github.com/Raji1009/Norm-of-a-matrix/assets/89059861/58a02584-18d5-4b09-980b-e573681044f2)


### Infinity Norm of a Matrix
![image](https://github.com/Raji1009/Norm-of-a-matrix/assets/89059861/55dc45b7-279e-4453-88a9-3c802a51c7b1)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
