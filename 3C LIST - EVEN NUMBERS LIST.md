# Exp.No:3c
## LIST - EVEN NUMBERS LIST

---

### AIM  
To write a Python function that accepts a number **N** and creates a list containing all even numbers up to **N**.

---

### ALGORITHM

1. Begin the program.  
2. Accept an integer `a` from the user.  
3. Create an empty list `l`.  
4. Use a `for` loop to iterate through numbers from `1` to `a - 1`:  
   - For each number `i`, check if it is even using `i % 2 == 0`.  
   - If it is even, append `i` to the list `l`.  
5. Print the final list `l` containing all the even numbers.  
6. Terminate the program.

---

### PROGRAM

```python
a = int(input("Enter an integer: "))
l = []
for i in range(1, a):
    if i % 2 == 0:
        l.append(i)
print("The list of even numbers is:", l)
```

### OUTPUT
![Screenshot 2025-05-01 125940](https://github.com/user-attachments/assets/f72f3dff-ad21-4c5c-a01d-a0964d636467)
### RESULT
Thus, the program was successfully executed and verified.
