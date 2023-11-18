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
Developed by: Manikandan.R
RegisterNumber: 23004754
'''
def max_marks(marks):
    return(max(marks))


```

ii)	# To find the maximum marks using the list method max().
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by: Manikandan.R
RegisterNumber: 23004754
'''
def max_marks(marks):
    return max(marks)


```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by: Manikandan.R
RegisterNumber: 23004754
'''
def max_marks(list1):
    max = list1[0]
    for x in list1:
        if x > max:
            max = x
    return max


```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
![image](https://github.com/Manikandanrag/FindMaximum/assets/138849491/ea848bfe-a89b-49a9-b305-9c9422f843bb)
![image](https://github.com/Manikandanrag/FindMaximum/assets/138849491/d799130f-8100-4488-93b3-93744e601cca)
![image](https://github.com/Manikandanrag/FindMaximum/assets/138849491/fd225318-ea3c-45fc-bd80-dd3f8da28fb2)



## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
