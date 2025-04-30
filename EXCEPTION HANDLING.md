# Exp.No:17  
## EXCEPTION HANDLING – EVEN OR ODD CHECK WITH VALUE ERROR HANDLING

---

### AIM  

To write a python program for the solution of value error in exception handling and check whether the number is even or odd.

---

### ALGORITHM

1. Begin the program.
2. Prompt the user to enter a number using input().
3. Use a try-except block to catch ValueError if the input cannot be converted to an integer.
4. Inside the try block:
    a. Convert the input to an integer.
    b. Check if the number is even or odd using modulus operator.
    c. Display the appropriate message.
5. In the except block:
    a. Display an error message asking the user to enter a valid number.
6. End the program.


---

### PROGRAM

```python
#Reg.No : 212223050032
#Name : Nidhish B

x = input()

if x.isdigit():
    x = int(x) 

    if x % 2 == 0:
        print('You entered even number')
    else:
        print('An odd number')
else:
    print("Enter only number")

```

### OUTPUT

![image](https://github.com/user-attachments/assets/fc95ae11-aea8-4c7c-83d3-8dc2a937a318)

### RESULT

The Python program successfully handles value errors and determines whether a number is even or odd.
