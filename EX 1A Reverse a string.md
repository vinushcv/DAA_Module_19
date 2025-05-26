# EX 1A Reverse a String
## DATE:
## AIM:
To write a program to create a recursive function to reverse a string.

## Algorithm
1.Take input string s from the user.

2.If the length of s is 0, return s.

3.Otherwise, get the last character of the string s[-1].

4.Recursively call the function on the substring excluding the last character s[:-1].

5.Concatenate the last character with the result of the recursive call and return it.

## Program:
```
Program to implement Reverse a String
Developed by: Vinush CV
Register Number: 212222230176
```
```python

def reverse_string(s):
    if len(s) == 0:  
        return s
    else:
        return s[-1] + reverse_string(s[:-1]) 

input_string = input()
reversed_string = reverse_string(input_string)
print(reversed_string)
```

## Output:
![image](https://github.com/user-attachments/assets/05c7cd04-9766-4b86-9c3f-a12b95331e48)


## Result:
The program successfully reverses the input string using recursion. When the user provides an input string, the output displays the reversed version of the string
