
## DICTIONARY - SIZE OF DICTIONARY

---

## AIM  

Write a python program to Sorting the Keys and Values in Alphabetical Order using the Key in Dictionary.
---

### ALGORITHM

1. Begin the program.
2. Define a dictionary with unsorted key-value pairs.
3. Use the sorted() function with dictionary.items() to sort the dictionary by keys.
4. Loop through the sorted items and print each key-value pair.
5. Terminate the program.

---

### PROGRAM

```python

# Name: Nidhish B
# Reg.No: 212223050032


input_dict = {2: 56, 1: 2, 5: 12, 4: 24, 6: 18, 3: 323}

sorted_items = sorted(input_dict.items())

print("Keys and Values sorted in alphabetical order by the key")
for key, value in sorted_items:
    print(f"({key}, {value})", end=" ")


```

### OUTPUT

![image](https://github.com/user-attachments/assets/cd8800c8-638a-49ab-a471-4a1ad79a536e)


### RESULT

Thus the python program to Sort the keys and values in alphabetical order using the Key in dictionary is successfully executed.
