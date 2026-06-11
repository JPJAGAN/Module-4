## Dictionary Operations in Python: Merging Two Dictionaries
## Aim
To write a Python program that merges two dictionaries and combines their key-value pairs.

## Algorithm

Define two dictionaries dict1 and dict2 with some key-value pairs.
Define a function merge() that merges the two dictionaries using the ** unpacking operator.
The merged result will combine keys from both dictionaries. If a key exists in both, the value from dict2 will overwrite that from dict1.
Call the merge() function and print the merged dictionary.
## Program

dict1={'Ten': 10,'Twenty': 20,'Thirty': 30} 
dict2={'Thirty': 30,'Fourty': 40,'Fifty': 50} def 
merge (dict1,dict2): 
res={**dict1 , **dict2} return 
res 
dict3=merge(dict1,dict2) 
print(dict3)
## Output

<img width="1005" height="197" alt="{1DC80B0A-CD84-4D41-8C32-D81D414168AF}" src="https://github.com/user-attachments/assets/403358f9-7dd8-441b-b27d-390513eaa401"/>

## Result
thus,the program has been executed successfully.
