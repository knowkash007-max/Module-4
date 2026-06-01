# Classes and Objects in Python: Calculate the Area of a Circle

## 🎯 Aim
To write a Python program that calculates the **area of a circle** based on the radius provided by the user. This program uses a class named `cse` and a method `mech` to perform the calculation.

## 🧠 Algorithm
1. **Get user input**: Take the radius of the circle as input from the user.
2. **Define the class**: Create a class named `cse`.
3. **Define the method**: Inside the class, define the method `mech` to calculate the area of the circle using the formula:  
   Area = pi *r^2 
4. **Execute the program**: Create an object of the class and call the method with the radius value.

## 🧾 Program
```
import math
pi_value=math.pi
class cse:
    def mech(self,radius):
        circle_area=(radius**2)*(pi_value)
        return round(circle_area,2)
radius=int(input())
circle1=cse()
print("Area of circle:",circle1.mech(radius))
```
## Output
<img width="750" height="228" alt="image" src="https://github.com/user-attachments/assets/81627b82-0d67-4e9c-82f7-ce635a81bc2f" />

## Result
Successfully wrote a Python program that calculates the area of a circle based on the radius provided by the user. This program uses a class named cse and a method mech to perform the calculation.
