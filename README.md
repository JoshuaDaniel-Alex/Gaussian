# Gaussian Elimination

## AIM:
To write a program to find the solution of a matrix using Gaussian Elimination.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Read the number of unknowns and input the augmented matrix of the system.
2. Apply forward elimination to convert the matrix into upper triangular form, checking that no pivot element is zero.
3. Perform back substitution starting from the last equation to calculate the values of the unknowns.
4. Display the computed values of all variables.

## Program:
```
/*
Program to find the solution of a matrix using Gaussian Elimination.
Developed by: Joshua Daniel A
RegisterNumber: 212225040161 (25017654)

for i in range(n):
    for j in range (n+1):
        a[i][j]=float(input())
for i in range(n):
    if a[i][j]==0:
        sys.exit('Divide by zero detected!')
    for j in range(i+1,n):
        ratio=a[j][i]/a[i][i]
        for k in range(n+1):
            a[j][k]=a[j][k]-ratio*a[i][k]
x[n-1]=a[n-1][n]/a[n-1][n-1]
for i in range(n-2,-1,-1):
    x[i]=a[i][n]
    for j in range(i+1,n):
        x[i]=x[i]-a[i][j]*x[j]
    x[i]=x[i]/a[i][i]
for i in range(n):
    print('X%d = %0.2f'%(i,x[i]),end=' ')
*/
```

## Output:
<img width="1255" height="432" alt="Screenshot 2026-02-12 084313" src="https://github.com/user-attachments/assets/675b6e04-8616-4091-ae79-227313cac972" />



## Result:
Thus the program to find the solution of a matrix using Gaussian Elimination is written and verified using python programming.

