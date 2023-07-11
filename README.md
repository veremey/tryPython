# Learn Python

Print text 20 times:

```
for i in range(10):
  print("Hello, World!")
```

Defining Functions:

```
def greetin(name):
  print("Welokme " + name)
```

Comparing Things

```
print(10>1)
>>> True
```

```
print(32 == 30+2)
>>> True
```

The == operator checks if the 2 values are
equal to each other. If they are equal,
Python returns a True result.

```
print(5+10 == 6+7)
>>> False
```

If the two values are not equal, as in the
expression 5+10 == 6+7 (or 15 == 13), Python  
returns a False result.

```
print(10-4 != 10+4)
>>> True
```

The != operator checks if the 2 values are
NOT equal to each other. If true, Python  
returns a True result.

```
print(9/3 != 3*1)
False
```

In this last example, 9/3 != 3\*1 (or 3 != 3)
is false. So, Python returns a False value.

The == operator can check if two strings are equal to each other.
If they are equal, the Python interpreter returns a True result.

```
print("a string" == "a string")
True
```

In this example, the equality == comparison is between "4 + 5" and
4 + 5. Since the left data type is a string and the right data type
is an integer, the two values cannot be equal. So, the comparison
returns a False result.

```
print("4 + 5" == 4 + 5)
False
```

The greater than > operator checks if the left string has a higher
Unicode value than the right string. If true, the Python interpreter
returns a True result. Since W has a Unicode value of 87, and you can
easily calculate that F has a Unicode value of 70, this comparison is
the same as 87 > 70. As this is true, Python will return a True
result.

```
print("Wednesday" > "Friday")
True
```
