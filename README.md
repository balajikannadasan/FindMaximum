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
def max_marks(marks):
    marks.sort()
    large = marks[-1]
    return large


```

ii)	# To find the maximum marks using the list method max().
```Python
def max_marks(marks):
  a=max(marks)
  return a 


```

iii) # To find the maximum marks without using builtin functions.
```Python
def max_marks(list1):
    max1=list1[0]
    for i in list1:
        if i>max1:
            max1 = i
    return max1


```



## Output:

i)	 To find the maximum of marks using the list method sort. 
![output](./img/1.png)

ii)	# To find the maximum marks using the list method max().
![output](./img/2.png)

iii) # To find the maximum marks without using builtin functions.
![output](./img/3.png)





## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.