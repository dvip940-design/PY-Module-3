# Strings-Palindrome Check in Python (Without Built-in Functions)

## 🎯 Aim
To write a Python program to check whether the string `"google"` is a **palindrome** or not, without using built-in palindrome checking functions.

## 🧠 Algorithm
1. Assign the string `"google"` to a variable.
2. Reverse the string manually using slicing (`[::-1]`).
3. Compare the original string with the reversed string.
   - If they are equal, print that the string is a palindrome.
   - Otherwise, print that it is not a palindrome.
4. Execute the program.

## 🧾 Program

Add code here
```p
s = "google"
rev = s[::-1]

if s == rev:
    print("Palindrome")
else:
    print("Not Palindrome")
```
## Output
<img width="1846" height="523" alt="image" src="https://github.com/user-attachments/assets/3dfc0cb2-ee4b-4dfe-b76a-9ec0fe99c6ab" />

## Result
Thus, the Python program to check whether the string "google" is a palindrome was successfully executed and verified.
