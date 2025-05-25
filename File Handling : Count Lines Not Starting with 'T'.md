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
Add code here

count = 0

with open("story.txt", "r") as file:

    for line in file:
    
        if line.strip() and not line.lstrip().startswith('T'):
        
            count += 1
            
print("Sum :", count)

## Output

![441164641-de4b06a9-8c3d-4964-9427-2a0f9239d647](https://github.com/user-attachments/assets/480c88c5-3de1-473e-9bf4-119589e688cb)



## Result

Thus the program that counts the number of lines in a text file story.txt that do not start with the alphabet 'T' is executed successfully.
