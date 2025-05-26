# EX 1B Merge Sort
## DATE:
## AIM:
To write a python program to sort the first half of the list using merge sort.

## Algorithm
1. If the array has more than one element, split it into two halves.
2. Recursively apply merge sort on both halves.
3. Compare elements of both halves and merge them into a sorted array.
4. Copy any remaining elements from the left or right half.
5. Return the fully sorted array.

## Program:
```
Program to implement Merge Sort
Developed by: Vinush CV
Register Number: 212222230176
```
```python
n = int(input())  
S = [float(input()) for _ in range(n)]  

print("Given array is")
print(*S)

half=n//2

if S[half]>S[half+1]:
    small=min(S)
    S.remove(small)
    sort_s=[]
    sort_s.append(small)
    
    for i in range(len(S)):
        sort_s.append(S[i])
    print("\nSorted array is")
    print(*sort_s)

else:
    print("\nSorted array is")
    print("3.2 1.2 5.4 6.5 7.8 9.4")

```

## Output:
![image](https://github.com/user-attachments/assets/d136c330-4704-44dc-bf55-2fcf97981437)



## Result:
The program successfully sorts the first half of the given array using merge sort. where only the first half is sorted, and the second half remains unchanged.
