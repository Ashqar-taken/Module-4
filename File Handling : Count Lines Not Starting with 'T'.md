# File Handling in Python: Count Lines Not Starting with 'T'

## 🎯 Aim
To write a Python program that counts the number of lines in a text file `story.txt` that do **not** start with the alphabet `'T'`.

## 🧠 Algorithm
1. Open the file `story.txt` in **read mode**.
2. Initialize a counter `count` to zero.
3. Iterate through each line of the file:
   - Check if the first character of the line is **not** `'T'`.
   - If the line does not start with `'T'`, increment the `count` by 1.
4. After processing all lines, print the `count` value, which represents the number of lines that do not start with `'T'`.

## 🧾 Program
```
Developed By: Ashqar Ahamed S.T
Register No: 212224240018
```
```
with open ('C:\\College\\SEM 2\\Python\\Exp4\\Exp4(5)\\story.txt','r') as text_file:
    file = text_file.readlines()
    for line in file:
        print(line,end='')

    count = 0
    for line in file:
        if not line.startswith('T'):
            count += 1
    
print("The number of lines not starting with with 'T':",count);
```

## Output

![Screenshot 2025-05-24 195027](https://github.com/user-attachments/assets/3928214b-30dc-40bd-b23b-9442b0815e86)

## Result
a Python program that counts the number of lines in a text file `story.txt` that do **not** start with the alphabet `'T'` was written successfully.
