# Module-3
# 🧹 Strings-Remove Nth Index Character from a String

## 🎯 Aim
To write a Python program that accepts a string and removes the character at a specified index.

## 🧠 Algorithm
1. Define a function named `remove` that takes the input string as an argument.
2. Read the index `n` from the user input.
3. Initialize an empty string `a` to store the new string.
4. Iterate over each index of the string using a `for` loop.
5. Check if the current index `i` is not equal to `n`.
6. If `i != n`, append the character at index `i` to string `a`.
7. After the loop, return the modified string `a`.
8. Print the final result.

## 💻 Program
Add Code Here
```p
def remove(string):
    n = int(input("Enter the index to remove: "))
    a = ""

    for i in range(len(string)):
        if i != n:
            a += string[i]

    return a

string = input("Enter a string: ")
print(remove(string))
```
## Output
<img width="1848" height="493" alt="image" src="https://github.com/user-attachments/assets/32375499-1d1e-4092-aa1e-f35b322ee573" />

## Result
Thus, the Python program to remove the character at a specified index from a string was successfully executed and verified.
