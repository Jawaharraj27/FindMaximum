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
Program to mark the maximum of marks using the list method sort
Developed by:JAWAHAR RAJ N 
RegisterNumber: 23000787
'''
def max_marks(marks):
    return(max(marks))

```

ii)	# To find the maximum marks using the list method max().
```Python

Program to find the maximum marks using the list method max().
Developed by: JAWAHAR RAJ N
RegisterNumber: 23000787
'''
def max_marks(list1):
    max=list1[0]
    for x in list1:
        if x>max:
            max=x
    return max

```

iii) # To find the maximum marks without using builtin functions.
```Python
Program to the maximum marks without using builtin functions.
Developed by: JAWAHAR RAJ N
RegisterNumber:23000787 
'''
def max_marks(list1):
    max=list1[0]
    for x in list1:
        if x>max:
            max=x
    return max
    


```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output1:
![Screenshot 2023-11-24 053223](https://github.com/Jawaharraj27/FindMaximum/assets/139842416/142d63d8-719d-4ce2-baec-7880b7a94198)
![Screenshot 2023-11-24 053231](https://github.com/Jawaharraj27/FindMaximum/assets/139842416/a64d95b9-0795-46b9-87f8-8df714b1e46b)
## Output2:
![Screenshot 2023-11-24 115951](https://github.com/Jawaharraj27/FindMaximum/assets/139842416/9c99759a-9031-4fa2-ab4d-1f48735006f1)

![Screenshot 2023-11-24 053231](https://github.com/Jawaharraj27/FindMaximum/assets/139842416/3a51ed91-5c5f-429b-8d5b-bd7a73342ba5)
## Output3:
![image](https://github.com/Jawaharraj27/FindMaximum/assets/139842416/d5050380-7dc5-4ffa-b30a-e0376c54a536)

![Screenshot 2023-11-24 053231](https://github.com/Jawaharraj27/FindMaximum/assets/139842416/afa07fe2-7f84-4a74-8cac-5011dd66dd46)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
