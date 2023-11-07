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
```
''' 
Program to mark the maximum of marks using the list method sort
Developed by: Sriram.V
RegisterNumber: 23013561
'''
def max_marks(marks):
    temp = 0
    for i in marks:
        if temp<i:
            temp = i
    return temp
```
ii)	# To find the maximum marks using the list method max().
```
''' 
Program to find the maximum marks using the list method max().
Developed by: Sriram.V
RegisterNumber: 23013561
'''
def max_marks(marks):
    marks.sort()
    large = marks[-1]
    return large
```
iii) # To find the maximum marks without using builtin functions.
```
''' 
Program to the maximum marks without using builtin functions.
Developed by: Sriram.V
RegisterNumber: 23013561
'''
def max_marks(list1):
    list1.sort()
    large = list1[-1]
    return large
```
## Sample Input and Output
![output](./img/max_marks1.jpg) 
## Output:
i)	# To find the maximum of marks using the list method sort.
![image](https://github.com/Darkwebnew/FindMaximum/assets/143114486/32c948d6-56c5-4b1d-a984-265dd211f88a)
ii)	# To find the maximum marks using the list method max().
![image](https://github.com/Darkwebnew/FindMaximum/assets/143114486/7f195a97-0a24-475c-be7d-9f4bacd8b91c)
iii) # To find the maximum marks without using builtin functions.
![image](https://github.com/Darkwebnew/FindMaximum/assets/143114486/c4b44e05-5dbc-4e6f-9f5e-26d9ea57b925)
## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
