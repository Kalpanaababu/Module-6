# Python OOP: Encapsulation with Private Members

## AIM

To implement **Encapsulation** in Python by defining a class `Rectangle` with **private member variables** `__length` and `__breadth`.

---

## ALGORITHM

1. **Define the Class**:
   - Create a class `Rectangle` with two private attributes: `__length` and `__breadth`.

2. **Initialize Variables**:
   - Use the `__init__()` constructor to set initial values for `__length` and `__breadth`.

3. **Print Values**:
   - Display the private variables from within the class to demonstrate access.

4. **Instantiate the Object**:
   - Create an object of the `Rectangle` class to trigger the constructor.

---

## Program

```
Developed By : Kalpanaa Babu T M
Reg No : 212224230112

class Rectangle:
    def __init__(self, length, width):
        self.__length = length  # Private variable
        self.__width = width    # Private variable
    
    def print_values(self):
        print(self.__length)
        print(self.__width)

rect = Rectangle(5, 3)

rect.print_values()
```

## Output

<img width="315" height="200" alt="image" src="https://github.com/user-attachments/assets/d4b24e60-f28d-49a5-ac83-2fba55e37573" />

## Result

Thus the output is executed successfully.
