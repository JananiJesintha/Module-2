# Exp.No:2e  
## SEB - Sum of all even numbers

---

### AIM  
To write a Python program to display the sum of all even numbers in the given range.

---

### ALGORITHM

1.Read two numbers m and n.
2.Initialize sum = 0.
3.For each number i from m to n:
4.If i is even, add it to sum.
5.Print the final sum.
6.End.

---

### PROGRAM
```
m=int(input())
n=int(input())
sum=0
for i in range(m,n+1):
    if i%2==0:
        sum+=i
print(f"Sum is : {sum}")        
```
### OUTPUT

<img width="842" height="393" alt="image" src="https://github.com/user-attachments/assets/4f761245-6be3-4332-85e4-634f31c8d1af" />

### RESULT
Thus, the python code is written and executed successfully.
