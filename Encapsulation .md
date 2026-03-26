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
    def __init__(self,length,breadth):
        self.__length = length
        self.__breadth = breadth
        
    def display(self):
        print(self.__length)
        print(self.__breadth)
        
obj = Rectangle(5,3)


print(obj._Rectangle__length)
print(obj._Rectangle__breadth)
```
## Output
<img width="305" height="146" alt="image" src="https://github.com/user-attachments/assets/290dfec5-c272-4b9d-908f-d22ae80a74e3" />

## Result
Thus, the program is successfully executed.
