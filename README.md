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
```
Program to mark the maximum of marks using the list method sort
Developed by: harini.m.d
RegisterNumber: 22001980
```

i)	# To find the maximum of marks using the list method sort.
```
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large

```

ii)	# To find the maximum marks using the list method max().
```
def max_marks(marks):
    m=max(marks)
    return m
    
```

iii) # To find the maximum marks without using builtin functions.
```
def max_marks(list1):
    max1=list1[0]
    for i in list1:
        if i>max1:
            max1=i
    return max1
```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
### The maximum of marks using the list method sort.
![output 1](https://user-images.githubusercontent.com/113497680/190687007-b4db72fe-86a2-40ec-bb93-60f8c13f9337.jpeg)

### the maximum marks using the list method max().
![output 1](https://user-images.githubusercontent.com/113497680/190687007-b4db72fe-86a2-40ec-bb93-60f8c13f9337.jpeg)

### the maximum marks without using builtin functions.
![output 3](![Screenshot from 2022-09-17 14-40-31](https://user-images.githubusercontent.com/113497680/190849470-71d218b2-bc4d-463d-a344-1aa7033ac831.png)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
