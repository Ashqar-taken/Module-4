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
Developed By: Ashqar Ahamed S.T
Register no: 212224240018
```
```
class cse:
    def mech(self,r):
        ar = 3.1416*(r**2)
        return ar 

a = int(input("Enter the radius of the circle: "))
circle = cse()
Area = circle.mech(a)
print("The Area of the Circle is: ",Area)
```

## Output

![Screenshot 2025-05-24 190156](https://github.com/user-attachments/assets/fc04426f-78af-4c10-a5c9-4b66972ed3b4)

## Result
A Python program that calculates the **area of a circle** based on the radius provided by the user. This program uses a class named `cse` and a method `mech` to perform the calculation was written successfully.
