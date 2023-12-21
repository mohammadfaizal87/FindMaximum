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
```Py
''' 
Program to mark the maximum of marks using the list method sort
Developed by: MOHAMMAD FAIZAL S K
RegisterNumber:23013519 
'''
def max_marks(marks):
    l=marks
    l.sort
    return max(l)



```

ii)	# To find the maximum marks using the list method max().
```py
''' 
Program to find the maximum marks using the list method max().
Developed by: MOHAMMAD FAIZAL S K
RegisterNumber:23013519 
'''
def max_marks(marks):
   return max(marks)



```

iii) # To find the maximum marks without using builtin functions.
```Py
''' 
Program to the maximum marks without using builtin functions.
Developed by: MOHAMMAD FAIZAL S K
RegisterNumber:23013519 
'''
def max_marks(list1):
    max1=0
    for i in list1:
        if max1<i:
          max1=i
    return max1



```



## Output:
![](output1.png)
![](output2.png)
![](output3.png)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.