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
Developed by:Gokul.m 
RegisterNumber: 22009089
'''
def max_marks(marks):
    marks.sort(reverse=True)
    n=marks[0]
    return n


```

ii)	# To find the maximum marks using the list method max().
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by: gokul.m
RegisterNumber: 22009089
'''
def max_marks(marks):
    m=max(marks)
    return m


```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by: gokul.m
RegisterNumber: 22009089
'''
def max_marks(list1):
    a=0
    for i in list1:
        if i>a:
            a=i
    return a


```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
![Screenshot (33)](https://user-images.githubusercontent.com/119560349/215334090-272be7d0-643b-42b2-87f1-baa5941afb9f.png)
![Screenshot 34](https://user-images.githubusercontent.com/119560349/215334096-504ec3d2-8cc0-45fa-9ed9-10c3043eae39.png)
![Screenshot (35](https://user-images.githubusercontent.com/119560349/215334105-44f2f5d5-9eba-4534-adee-384860a8e790.png)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
