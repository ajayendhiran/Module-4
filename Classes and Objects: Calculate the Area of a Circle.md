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
<img width="602" height="187" alt="503011062-b35431b5-b7f1-432f-b56a-570bd7fa9944" src="https://github.com/user-attachments/assets/30857987-778f-4dd8-83e7-a1cd2889c75d" />


## Result
Successfully wrote a Python program that calculates the area of a circle based on the radius provided by the user. This program uses a class named cse and a method mech to perform the calculation.
