# Find the maximum of a list of numbers
## Aim:
To write a program to find the maximum of a list of numbers.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1.	Get the list of marks as input
2.	Use the sort() function or max() function or use the for loop to find the maximum mark.
3.	Return the maximum value
## Program:

i)	# To find the maximum of marks using the list method sort.
```Python
Program to mark the maximum of marks using the list method sort
Developed by: GOWTHAM N
RegisterNumber: 23013437
def max_marks(marks):
    marks.sort()
    z=marks[-1]
    return z
```

ii)	# To find the maximum marks using the list method max().
```Python
Program to find the maximum marks using the list method max().
Developed by: GOWTHAM N
RegisterNumber: 23013437
def max_marks(marks):
    marks.sort()
    a=marks[-1]
    return a
```

iii) # To find the maximum marks without using builtin functions.
```Python
Program to the maximum marks without using builtin functions.
Developed by: GOWTHAM N
RegisterNumber: 23013437
def max_marks(list1):
    list1.sort()
    x=list1[-1]
    return x
```
## Sample Input and Output
![output](./img/max_marks1.jpg) 
![output](https://github.com/GOWTHAM54577/FindMaximum/assets/144589420/7e8f7b0f-5cc6-4180-9ea5-49bd1ba9f116)
![output](https://github.com/GOWTHAM54577/FindMaximum/assets/144589420/32d6151c-26c6-4d3c-bce0-392aea9b0a2b)
![output](https://github.com/GOWTHAM54577/FindMaximum/assets/144589420/2f962881-7b62-43b5-aa0e-608ca9f61a83)



## Output:
![Output](https://github.com/GOWTHAM54577/FindMaximum/assets/144589420/41481c6c-de92-4fb2-b7ef-264820e3349d)
![Output](https://github.com/GOWTHAM54577/FindMaximum/assets/144589420/bc26baaf-4833-43d1-85d9-655c2e3942d7)
![Output](https://github.com/GOWTHAM54577/FindMaximum/assets/144589420/1e6d9b0b-5526-4cdd-afa9-d6af09df98f0)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
