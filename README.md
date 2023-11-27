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
![output]![max of marks list 1 question](https://github.com/tamizhselvan23013460/FindMaximum/assets/150231370/2963d5b9-c23d-4e34-841b-549ad6f0165e)
![output]![max of mark list 2 question](https://github.com/tamizhselvan23013460/FindMaximum/assets/150231370/9ca48504-0c16-4001-80ae-c315d5c06f38)
![output]![max of mark list question 3](https://github.com/tamizhselvan23013460/FindMaximum/assets/150231370/45b633bf-59c4-428a-809e-a8e6e07affe4)



## Output:
![output]![max of mark list 1](https://github.com/tamizhselvan23013460/FindMaximum/assets/150231370/04d64c68-0a2c-43e3-99c5-2e5b82ceec60)

![output]![max of list mark 2 ](https://github.com/tamizhselvan23013460/FindMaximum/assets/150231370/fce9fc1c-58cf-4f92-8333-ee07e33d6636)

![output]![max of mark list 3](https://github.com/tamizhselvan23013460/FindMaximum/assets/150231370/11df48f7-0ec8-4ba9-b6c8-272f1c9379e2)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
