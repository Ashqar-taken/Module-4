## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program
```
Developed By: Ashqar Ahamed S.T
Register No: 212224240018
```
```
dict1 = {'a':12, 'b': 32,'c':25,'d':89}
dict2 = { 'c':35,'g':46,'e':90}
print("Dictionary 1: ",dict1)
print("Dictionary 2: ",dict2)

def merge(dict1,dict2):
    data = {**dict1,**dict2}
    return data

Dict = merge(dict1,dict2)
print("The merged Dictionary is: ",Dict)
```

## Output

![Screenshot 2025-05-24 191105](https://github.com/user-attachments/assets/34f811c6-4c6a-4195-8aae-c97b4afdf7cf)

## Result
A Python program that merges **two dictionaries** and combines their key-value pairs was written successfully.
