# Selection sort and Insertion sort
## Aim:
To write a program to perform selection sort and insertion sort using python programming.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
## Selection Sort Algorithm:
1.	Set the first unsorted element as the minimum
2.	For each of the unsorted elements, check if the element < current minimum.
3.	If yes, set the element as the new minimum.
4.	Swap minimum with first unsorted position.
5.	Repeat the steps 2 and 3 for all the elements in the array.
## Insertion Sort Algorithm:
1.	Set the first element as sorted element j.
2.	For each unsorted element X, check if current sorted element j >X.
3.	If yes, move sorted element to the right by 1.
4.	Break the loop and insert X.
5.	Repeat the steps 2 to 4 for sorting all the elements in the array.
## Program:
i)	#Selection Sort

#Deveolped by:BAUDHIGAN D

#Register no:212223230028


````
num=eval(input())
for i in range(len(num)):
    low=i
    for j in range(i+1,len(num)):
        if num[j]<num[low]:
            low=j
    num[i],num[low]=num[low],num[i]
print(num)
````

ii)	#Insertion Sort

#Deveolped by:BAUDHIGAN D

#Register no:212223230028

```
num=eval(input())
for i in range(1,len(num)):
    insert=num[i]
    j=i-1
    while j>=0 and num[j]>=insert:
        num[j+1]=num[j]
        j=j-1
    num[j+1]=insert
print(num)
```

## Output:
![Screenshot 2024-05-10 104256](https://github.com/baudhigan/Sorting-Algorithms/assets/151921158/4e2b9e1e-2798-4d63-9489-13ce237bc558)

![Screenshot 2024-05-10 104325](https://github.com/baudhigan/Sorting-Algorithms/assets/151921158/435e1511-1db9-42d6-8da3-6cc60fb77353)

## Result:
Thus the program is written to perform selection sort and insertion sort using python programming.
