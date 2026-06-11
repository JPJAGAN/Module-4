## Dictionary-Python Program to Sort a Dictionary by Keys and Values
This Python program demonstrates how to sort a dictionary:

Alphabetically by keys
Alphabetically by values
## Aim
To write a Python program that sorts a dictionary's:

Keys in alphabetical order
Values in alphabetical order
## Algorithm
Start the program.
Define a dictionary with key-value pairs.
Sort by Keys:
Use sorted(dictionary.items())
Convert the result to a dictionary using dict()
Sort by Values:
Use sorted(dictionary.items(), key=lambda item: item[1])
Convert the result to a dictionary using dict()
Display the original and sorted dictionaries.
End the program.
## Program
```
def dictionairy():  
 key_value ={}   
 key_value[2] = 56      
 key_value[1] = 2
 key_value[5] = 12
 key_value[4] = 24
 key_value[6] = 18     
 key_value[3] = 323
 s=sorted(key_value.items(),key=lambda x:x[1])
 print ("Keys and Values sorted in alphabetical order by the value")
 print(s)
 
def main():
    
    dictionairy()           
```
## Sample Output

<img width="1003" height="249" alt="{2FEBBE62-74F5-4B16-B79C-436AC715572F}" src="https://github.com/user-attachments/assets/0c9f94b7-b685-48a5-a7b9-089b4e2d0e77"/>

## Result
The program successfully sorts the dictionary by its keys and values in alphabetical order and prints both sorted versions along with the original dictionary.
