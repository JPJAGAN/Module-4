## Exception Handling in Python: Avoiding Index Errors
## Aim
To write a Python program that handles an IndexError when trying to access an element beyond the available range of a list.

## Algorithm
Define a list list1 with some integer elements.
Use a try-except block:
In the try block, attempt to access an index that is out of range (e.g., list1[5]).
In the except block, catch the error and print a custom message "You're out of list range".
Print the result based on whether the index access succeeds or fails.
## Program
```
try:
    # Taking 3 elements input from the user
    L = []
    for i in range(3):
        item = ['laptop','mobile','pen']
        L.append(item)

    # Trying to access index 4
    print(L[4])

except IndexError:
    print("check index range")
```
## Output
<img width="979" height="269" alt="{2A8278F5-A5AA-43F9-9472-15714540F053}" src="https://github.com/user-attachments/assets/6eb85032-9c7a-4d1a-bde1-a9888693bb63" />

## Result
Thus the program executed successfully.
