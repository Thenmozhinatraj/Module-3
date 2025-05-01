# Exp.No:3b  
## REGEX - PATTERN MATCHING USING REGEX

---

### AIM  
To write a Python program that matches a string containing an `'a'` followed by **two to three `'b'` characters** using regular expressions.

---

### ALGORITHM

1. Begin the program.  
2. Accept a string `str1` from the user.  
3. Define the regular expression pattern as `r"[a]+b{2,3}"`.  
4. Use the `re.match()` function to check if the string `str1` matches the pattern.  
5. If a match is found, print `"Found a match!"`.  
6. If no match is found, print `"Not matched!"`.  
7. Terminate the program.
---

### PROGRAM

```python
import re
str1 = input("Enter a string: ")
pattern = r"[a]+b{2,3}"
if re.match(pattern, str1):
    print("Found a match!")
else:
    print("Not matched!")
```
### OUTPUT
![Screenshot 2025-05-01 125627](https://github.com/user-attachments/assets/a34f1447-83b4-4b48-803c-26e0abea74be)

### RESULT
The program was executed successfully, and the output has been verified.
