# 🐍 Python OOP: Encapsulation with Private Members

## 🎯 AIM

To implement **Encapsulation** in Python by defining a class `Rectangle` with **private member variables** `__length` and `__breadth`.

---

## 🧠 ALGORITHM

1. **Define the Class**:
   - Create a class `Rectangle` with two private attributes: `__length` and `__breadth`.

2. **Initialize Variables**:
   - Use the `__init__()` constructor to set initial values for `__length` and `__breadth`.

3. **Print Values**:
   - Display the private variables from within the class to demonstrate access.

4. **Instantiate the Object**:
   - Create an object of the `Rectangle` class to trigger the constructor.

---

## 💻 Program
```
class Rectangle:
    def __init__(self, length, width):
        self.__length = length   # private variable
        self.__width = width     # private variable

    def display(self):
        # Accessing private variables inside the class
        return self.__length
        return self.__width



r = Rectangle(5, 3)


r.display()


print(r._Rectangle__length)
print(r._Rectangle__width)
```

## Output


<img width="298" height="155" alt="Screenshot 2025-10-20 193013" src="https://github.com/user-attachments/assets/690b3cfe-6c56-4fda-bc69-a8ac0155a486" />


## Result
Thus,the python program has been executed successfully
