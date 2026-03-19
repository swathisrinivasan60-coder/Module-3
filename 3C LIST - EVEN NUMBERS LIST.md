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

```
n=eval(input())
l=[]
for i in range (n):
l.append(int(input()))
print("List =",l)
print("The maximum value is",max(l))
```

### OUTPUT
<img width="897" height="427" alt="image" src="https://github.com/user-attachments/assets/49d37079-cd7a-474b-9ebb-5bb22c3bf123" />


### RESULT
Thus the Python program to find the maximum value from a list using the max() function was executed successfully and the output was verified.
