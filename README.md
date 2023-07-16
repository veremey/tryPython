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

Example 1
Evaluate the output of this print statement

```
def product(a, b):
    return(a*b)

print(product(product(2,4), product(3,5)))
```

Example 2
Evaluate the output of this print statement

```
def difference(a, b):
    return(a-b)

def sum(a, b):
    return(a+b)

print(difference(sum(2,2), sum(3,3)))
```

Example 3
Evaluate the Boolean output of this comparison

```
print((5 >= 2*4) and (5 <= 4*3))
```

Example 4
Evaluate the value of the comparison in the if statement

```
x = 3
if x+5 > x**2 or x % 4 != 0:
  print("This comparison is True")
```

Example 5
Evaluate the output of this if-elif-else statement

```
number = 6
if number * 2 < 14:
    print(number * 6 % 3)
elif number > 7:
    print(100 / number)
else:
    print(7 - number)
```

```
IP_address = "192.168.1.10"
host_name = "Printer Server 1"
print(IP_address + " is the IP address of " + host_name)
```

Should print "192.168.1.10 is the IP address of Printer Server 1"

```
multiplier = 1
result = multiplier*5
while result <= 50:
  print(result)
  multiplier += 1
  result = multiplier*5
print("Done")
```

### while Loop Terms:

- while loop - Tells the computer to execute a set of instructions while a specified condition is True. In other words, while loops keep executing the same group of instructions until the condition becomes False.

- infinite loop - Missing a method for exiting the loop, causing the loop to run forever.

- break - A keyword that can be used to end a loop at a specific point.
