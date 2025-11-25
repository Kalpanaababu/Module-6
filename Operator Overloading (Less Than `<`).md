# Python OOP: Operator Overloading (Less Than `<`)

## AIM

To write a Python program that demonstrates **operator overloading** by overloading the **less than (`<`)** operator using a custom class.

---

## ALGORITHM

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

## Program

```
Developed By : Kalpanaa Babu T M
Reg No : 212224230112

class A:
    def __init__(self, a):
        self.a = a

    def __lt__(self, o):
        if self.a < o.a:
            return "ob1 is less than ob2"
        else:
            return "ob2 is less than ob1"

ob1 = A(int(input("Enter value for object 1: ")))
ob2 = A(int(input("Enter value for object 2: ")))

print(ob1 < ob2)
```

## Output

<img width="960" height="197" alt="image" src="https://github.com/user-attachments/assets/a14e9782-6b7f-4fd8-aed5-a48692c6a7d2" />

## Result

Thus the output is executed successfully.
