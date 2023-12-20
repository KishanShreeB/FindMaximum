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
''' 
Program to mark the maximum of marks using the list method sort
Developed by: Kishan Shree B
RegisterNumber: 23012867
'''
def max_marks(marks):
    #Write your code here
    list1=sorted(marks)
    maxi=list1[-1]
    return maxi


```

ii)	# To find the maximum marks using the list method max().
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by: Kishan Shree B
RegisterNumber: 23012867
'''
def max_marks(marks):
    # write your code here
    list1=max(marks)
    return list1


```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by: Kishan Shree B
RegisterNumber: 23012867
'''
def max_marks(marks):
    # write your code here
    list1=max(marks)
    return list1


```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
![image](https://github.com/KishanShreeB/FindMaximum/assets/144870434/5cff35ab-424c-47c6-a89a-bc71975de166)
![image](https://github.com/KishanShreeB/FindMaximum/assets/144870434/399128de-4548-4b7e-9a9a-042e7f101f9a)
![image](https://github.com/KishanShreeB/FindMaximum/assets/144870434/c981e0e9-98f1-46df-914f-aadd633010a3)




## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
