
## CLASS AND OBJECTS - AREA OF CIRCLE

---

### AIM  

Write Python Program to take the radius from the user and find the area of the circle using class name 'saveetha' and function name 'slot'

---

### ALGORITHM

1. Begin the program.
2. Import the math module for using π (pi).
3. Define a class named 'saveetha'.
4. Inside the class, define a method 'slot' that takes the radius as a parameter.
5. In the 'slot' method, calculate the area of the circle using the formula: area = π * r².
6. Print the calculated area rounded to two decimal places.
7. In the main part of the program, take input for the radius from the user.
8. Create an object of the class 'saveetha'.
9. Call the 'slot' method using the created object and pass the radius.
10. End the program.

---

### PROGRAM

```python
# Name: Nidhish B
# Reg No:212223050032

import math
class saveetha:
    def slot(self,r):
        area=math.pi*r*r
        print('Area of circle:',round(area,2))
        
r=int(input())
obj=saveetha()
obj.slot(r)



```

### OUTPUT

![image](https://github.com/user-attachments/assets/aa4d8724-4b88-4402-84ed-39cf8a29e428)


### RESULT

The Python program successfully calculates and displays the area of a circle.
