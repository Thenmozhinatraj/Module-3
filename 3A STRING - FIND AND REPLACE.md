# Exp.No:3a
## STRING - FIND AND REPLACE

---

### AIM  
To write a Python function to accept a string, identify a word to be replaced, and replace it with a new word provided by the user.

---

### ALGORITHM

1. Begin the program.  
2. Input the original string `str1` and the word to be replaced `replace_str`.  
3. Ask the user to input the new replacement word `str2`.  
4. Use the `replace()` method in Python to replace all occurrences of `replace_str` in `str1` with `str2`.  
5. Store the modified string in `str3`.  
6. Display the original string (`str1`) and the modified string (`str3`).  
7. Terminate the program.

---

### PROGRAM

```python
def replacestr(s,d):
    a=input()
    f=s.replace(d,a)
    print("The old string is {}\nthe new string is {}".format(s,f))
```
### OUTPUT
![image](https://github.com/user-attachments/assets/ccc1b7a3-6ffd-49b8-b291-dafc71c2118d)


### RESULT
The program was successfully executed and the output is verified.

