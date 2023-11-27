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

### Using list sort method:
### Step 1:
Define the function max_marks that takes a list of marks as a parameter.
### Step 2:
Use the sort() method to sort the list of marks in ascending order.
### Step 3:
Get the last element of the sorted list, which is the largest mark.
### Step 4:
Return the largest mark.

### Using list max method:
### Step 1:
Define the function max_marks that takes a list of marks as a parameter.
### Step 2:
Use the max() function to find the maximum mark in the list.
### Step 3:
Return the maximum mark.

### Using list without builtin function:
### Step 1:
Define the function max_marks that takes a list of marks as a parameter.
### Step 2:
Initialize a variable 'max' with the first element of the list.
### Step 3:
Use a for loop to iterate through each element in the list.
### Step 4:
Check if the current mark is greater than the current maximum.
### Step 5:
If true, update the maximum value.
### Step 6:
Return the maximum mark.
## Program:

i)	# To find the maximum of marks using the list method sort.
```
''' 
Program to mark the maximum of marks using the list method sort
Developed by: Tamizhselvan.B
RegisterNumber: 23013460
'''
def max_marks(marks):
    marks.sort()
    large = marks[-1]
    return large

```

ii)	# To find the maximum marks using the list method max().
```
''' 
Program to find the maximum marks using the list method max().
Developed by: Tamizhselvan.B
RegisterNumber: 23013460
'''
def max_marks(marks):
     large=max(marks)
     return large

```

iii) # To find the maximum marks without using builtin functions.
```
''' 
Program to the maximum marks without using builtin functions.
Developed by: Tamizhselvan.B
RegisterNumber: 23013460
'''
def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i > max:
            max=i
    return max       

```
## Sample Input and Output
![output]![Alt text](<max of marks list 1 question.png>)
![output]![Alt text](<max of mark list 2 question.png>)
![output]![Alt text](<max of mark list question 3.png>)
## Output:
![output]![Alt text](<max of mark list 1.png>)
![output]![Alt text](<max of list mark 2 .png>)
![output]![Alt text](<max of mark list 3.png>)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
