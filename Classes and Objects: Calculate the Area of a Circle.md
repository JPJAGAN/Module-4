## Classes and Objects in Python: Calculate the Area of a Circle
## Aim
To write a Python program that calculates the area of a circle based on the radius provided by the user. This program uses a class named cse and a method mech to perform the calculation.

## Algorithm

Get user input: Take the radius of the circle as input from the user.
Define the class: Create a class named cse.
Define the method: Inside the class, define the method mech to calculate the area of the circle using the formula:
Area = pi *r^2
Execute the program: Create an object of the class and call the method with the radius value.

## Program
```
import math

class cse:
    def mech(self, radius):
        area = math.pi * radius ** 2
        print(f"Area of circle: {area:.2f}")


r = float(input())

obj = cse()
obj.mech(r)
```
### Output

<img width="1034" height="262" alt="{7FA31A39-0066-42E7-9D9B-9E9C5DF1AC43}" src="https://github.com/user-attachments/assets/27c80547-3afe-4b23-8b93-8dc7f6adca72"/>

## Result
Thus the program executed successfully.
