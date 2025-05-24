# Exception Handling in Python: Avoiding Index Errors

## 🎯 Aim
To write a Python program that handles an **IndexError** when trying to access an element beyond the available range of a list.

## 🧠 Algorithm
1. Define a list `list1` with some integer elements.
2. Use a **try-except** block:
   - In the `try` block, attempt to access an index that is out of range (e.g., `list1[5]`).
   - In the `except` block, catch the error and print a custom message `"You're out of list range"`.
3. Print the result based on whether the index access succeeds or fails.

## 🧾 Program
```
Developed By: Ashqar Ahamed S.T
Register No: 212224240018
```
```
list1 = [12,54,53,23]

try:
    print(list1[5])
except:
    print("You're out of list range")
```

## Output

![Screenshot 2025-05-24 192608](https://github.com/user-attachments/assets/18a26d43-63f8-4e36-8c07-9d153a3eb093)


## Result
a Python program that handles an **IndexError** when trying to access an element beyond the available range of a list was written successfully.
