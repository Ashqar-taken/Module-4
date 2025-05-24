# 🔤 Dictionary-Python Program to Sort a Dictionary by Keys and Values

This Python program demonstrates how to sort a dictionary:
- Alphabetically by keys
- Alphabetically by values

---

## 🎯 Aim

To write a Python program that sorts a dictionary's:
- Keys in alphabetical order
- Values in alphabetical order

---

## 🧠 Algorithm

1. **Start the program.**
2. **Define** a dictionary with key-value pairs.
3. **Sort by Keys**:
   - Use `sorted(dictionary.items())`
   - Convert the result to a dictionary using `dict()`
4. **Sort by Values**:
   - Use `sorted(dictionary.items(), key=lambda item: item[1])`
   - Convert the result to a dictionary using `dict()`
5. **Display** the original and sorted dictionaries.
6. **End the program.**

---

## 🧪Program
```
Developed By: Ashqar Ahamed S.T
Register No: 212224240018
```
```
dictionary = {'d':"Apple",'i':'Target','j':'Plane','s':"Spaceship",'c':"Baboon"}
dict1 = sorted(dictionary.items())
dict1 = dict(dict1)
dict2 = dict(sorted(dictionary.items(),key=lambda item: item[1]))
print("The orignal Dictionary: ",dictionary)
print("The Dictionary that is sorted by key: ",dict1)
print("The Dictionary that is sorted by values: ",dict2)
```
## Sample Output

![Screenshot 2025-05-24 192007](https://github.com/user-attachments/assets/7de45601-2dbc-405a-b0d9-3366a1cdccfb)

## Result
A Python program demonstrates how to sort a dictionary: Alphabetically by keys, Alphabetically by values was written successfully.
  

