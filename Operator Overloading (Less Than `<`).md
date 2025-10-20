# 🐍 Python OOP: Operator Overloading (Less Than `<`)

## 🎯 AIM

To write a Python program that demonstrates **operator overloading** by overloading the **less than (`<`)** operator using a custom class.

---

## 🧠 ALGORITHM

1. **Create Class `A`**:
   - Define the `__init__()` method to initialize the object with a value `a`.

2. **Overload the `<` Operator**:
   - Define the `__lt__()` method with logic:
     - If `self.a < o.a`, return `"ob1 is less than ob2"`
     - Else, return `"ob2 is less than ob1"`

3. **Create Objects**:
   - Instantiate two objects `ob1` and `ob2` with values.

4. **Use `<` Operator**:
   - Use `print(ob1 < ob2)` to trigger the overloaded behavior.

---

## 💻 Program
```
class A:
    def __init__(self,val):
        self.val=val
    def __lt__(self,oth):
        return self.val<oth.val
ob1=A(2)
ob2=A(3)
if ob1<ob2:
    print("ob1 is less than ob2")
else:
    print("ob1 is greater than ob2")
```

## Output

<img width="593" height="108" alt="Screenshot 2025-10-20 193909" src="https://github.com/user-attachments/assets/f728d559-ec68-4d5d-acab-f783117737e8" />



## Result
Thus,the python program has been executed successfully
