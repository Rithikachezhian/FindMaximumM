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
''' To mark the maximum of marks using the list method sort.
DEVELOPED BY: RITHIKA N
REGISTER NUMBER: 212223230172'''
def max_marks(array):
    array.sort()
    return array[-1]


```

ii)	# To find the maximum marks using the list method max().
```Python
''' to find the maximum marks using the list method max().
DEVELOPED BY: RITHIKA N
REGISTER NUMBER: 212223230172'''
def max_marks(array):
    return max (array)


```

iii) # To find the maximum marks without using builtin functions.
```Python
'''to find the maximum marks without using builtin functions.
DEVELOPED BY: RITHIKA N
REGISTER NUMBER: 212223230172'''
def max_marks(array):
    max1=array[0]
    for i in range(1,len(array)):
        if max1<array[i]:
            max1=array[i]
    return max1        


```



## Output:
![Screenshot 2024-04-23 004655](https://github.com/Rithikachezhian/FindMaximumM/assets/145742406/406d6c49-dcde-43e3-b48f-8a4ce1371a89)
![Screenshot 2024-04-23 004854](https://github.com/Rithikachezhian/FindMaximumM/assets/145742406/1224e00b-e895-4c65-b55c-ac43328e99a4)
![Screenshot 2024-04-23 004943](https://github.com/Rithikachezhian/FindMaximumM/assets/145742406/ded08293-0fbe-4266-8054-92aea98d071c)




## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
