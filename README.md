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
Program to mark the maximum of marks using the list method sort
Developed by: KUSHALI P G
RegisterNumber: 23012804
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large
    ```

ii)	# To find the maximum marks using the list method max().
''' 
Program to find the maximum marks using the list method max().
Developed by: KUSHALI P G
RegisterNumber:23012804 
def max_marks(marks):
    marks.sort()
    res=marks[-1]
    return res
```

iii) # To find the maximum marks without using builtin functions.
``` 
Program to the maximum marks without using builtin functions.
Developed by: 
RegisterNumber: 
def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i>max:
            max=i
    return max

```
## Sample Input and Output:
i)
![image](https://github.com/KUSHALI104/FindMaximum/assets/150231135/7b4ff867-30bd-4333-a0fe-54d7a4c7da58)
ii)
![image](https://github.com/KUSHALI104/FindMaximum/assets/150231135/907dbabc-0dc6-4a3d-bf8b-74e8208925ca)
iii)
![image](https://github.com/KUSHALI104/FindMaximum/assets/150231135/4b044a27-ec27-4b2c-b078-6d86c5d20699)

## Output:
i)
![image](https://github.com/KUSHALI104/FindMaximum/assets/150231135/68af8841-e7b9-4f1e-8558-92ccd7292c05)
ii)
![image](https://github.com/KUSHALI104/FindMaximum/assets/150231135/eacaf573-2da5-493b-b79d-2c89a73049d4)
iii)
![image](https://github.com/KUSHALI104/FindMaximum/assets/150231135/e40857f4-27b9-4b4e-915d-bc7a9b538ed1)




## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
