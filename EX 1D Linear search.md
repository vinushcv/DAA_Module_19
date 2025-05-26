# EX 1D Linear search
## DATE:
## AIM:
To write a python program for a search function with parameter list name and the value to be searched using string values.



## Algorithm
1. Check if the target exists: See if the input n is present within the List.
2. Report if found: If n is in List, the result is "Found".
3. Report if not found: Otherwise, if n is not in List, the result is "Not Found".
4. Get list length: Read the number of elements for the List.
5. Create and populate list: Take that many inputs and store them in the List.
6. Get search target: Read the value to be searched for (n).
7. Perform and display search: Call the search function and print its output.
## Program:
```
Program to implement a search function with parameter list name and the value to be searched using string values.
Developed by: Vinush CV
Register Number: 212222230176
```
```python
def search(List,n):
    if n in List:
        return "Found"
    return "Not Found"
    
length=int(input())
List=[input() for _ in range(length)]
n=input()
print(search(List,n))
```

## Output:
![image](https://github.com/user-attachments/assets/460b44fe-d941-43b9-9c56-7c63bea03b43)



## Result:
The program was executed successfully, and it correctly checks if the input element is present in the list, printing "Found" if the element exists or "Not Found" if it does not.
