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
```
def palindrome(a):
    x1=a[::-1]
    if a==x1:
       print("The entered string is palindrome")
    else:
        print("The entered string is not palindrome")

string =input()
palindrome(string)
```

## Output
<img width="777" height="127" alt="image" src="https://github.com/user-attachments/assets/3912969d-842f-4f39-adb1-6db1378f61da" />

## Result
Thus the program executed successfully.
