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

- **_while loop_** - Tells the computer to execute a set of instructions while a specified condition is True. In other words, while loops keep executing the same group of instructions until the condition becomes False.

- **_infinite loop_** - Missing a method for exiting the loop, causing the loop to run forever.

- **_break_** - A keyword that can be used to end a loop at a specific point.

```
def addition_table(given_number):

  iterated_number = 1
  my_sum = 1

  while iterated_number <= 5:
    my_sum = given_number + iterated_number

    if my_sum > 20:
        break

    print(str(given_number), "+", str(iterated_number), "=", str(my_sum))
    iterated_number += 1
```

_addition_table(5)_

_addition_table(17)_

_addition_table(30)_

_Expected output:_

_5 + 1 = 6_

_5 + 2 = 7_

_5 + 3 = 8_

_5 + 4 = 9_

_5 + 5 = 10_

_17 + 1 = 18_

_17 + 2 = 19_

_17 + 3 = 20_

_None_

### for Loop Terms

```
for n in range(0,11,2):
    print(n)
```

The loop should print 0, 2, 4, 6, 8, 10

```
for number in range(2,7+1):
    print(number)
```

The loop should print 2,3,4,5,6,7

```
for number in range(2,7):
    print(number)
```

The loop should print 2,3,4,5,6

---

The roles of the **range(start, stop, step)** function parameters are:

- **Start** - Beginning of range

  - value included in range

  - default = 0

- **Stop** - End of range

  - value excluded from range (to include, use stop+1)

  - no default

  - must provide the ending index number

- **Step** - Incremental value

  - default = 1

### for Loops vs. while Loops

for loops and while loops share several characteristics. Both loops can be used with a variety of data types, both can be nested, and both can be used with the keywords break and continue. However, there are important differences between the two types of loops:

- while loops are used when a segment of code needs to execute repeatedly **while** a condition is true

- for loops iterate over a sequence of elements, executing the body of the loop **for** each element in the sequence

### Nested for Loops

```
for x in sequence:
    # start of the outer loop body
    for y in sequence:
        # start of the inner loop body

        # end of of the inner loop body
    # continue body of the outer loop
    # end of the outer loop body
```

Example of a for Loop with Nested if Statement:

```
for x in range(7):
    if x % 2 == 0:
        print(x)
```

The loop should print 0, 2, 4, 6

**variables** - Know how to properly initialize or increment a variable. You will also need to recognize a coding error due to the failure to properly initialize or increment a variable.

**infinite loops** - Know how to recognize infinite loops and use common solutions to prevent them. For example, check loop conditions, ranges, iterators, control statements, etc. to ensure that at least one of these controls are in place to prevent an infinite loop.

**iterators** - Know the various options available for iterating a variable (e.g., using assignment operators, using the third range() function parameter). You will also need to analyze where the iteration should occur. A misplaced iterator could produce the wrong output or create an infinite loop.

**control statements** - Know how and when to use the break and continue control statements to prevent infinite loops.

**_range()_** Function Parameters - Know the roles of the three possible range(x, y, z) function parameters:

- **_x_** - Start of Range (included)

- **_y_** - End of Range (excluded index)

  To include the end of range index, use the expression y+1

  The end of range must be included in the range() parameters.

- **_z_** - Incremental value

_Example 1:_ **_range(4, 12+1, 2)_**

_This example creates a range that starts at 4 and ends at 12 (without the +1, the range would end at 11)._

_The third parameter increments the range iteration by 2, as opposed to the default increment of 1. The range(4, 12+1, 2) expression would produce the values: 4, 6, 8, 10, 12_

_Example 2:_ **_range(10, 2-1, -2)_**

_This example creates a range that starts at 10 and ends at 2-1, with a decremental value of -2. When counting down, to include the value of the end of the range index, use -1 (end of range minus 1). This range produces the sequence: 10, 8, 6, 4, 2_

**_print()_** Function Default Behavior - Know the default behavior of the **_print()_** function is to insert a new line character after the print statement runs.

To override the insertion of the new line character and replace it with a space, add end=" " as the last item in the **_print()_** parameters. This makes it possible to add the next print output to the same line, separated by a space. You might use this technique when a **_print()_** function is part of a for or while loop. Example syntax: **_print(x+1, end=" ")_**

---

## String Indexing and Slicing

String indexing allows you to access individual characters in a string.
If you try to access an index that’s larger than the length of your string, you’ll get an **_IndexError_**.
You can also access a portion of a string, called a **_slice_** or a **_substring_**. This allows you to access multiple characters of a string. You can do this by creating a range, using a colon as a separator between the start and end of the range, `like [2:5]`.

```
>>> fruit = "Mangosteen"
>>> fruit[1:4]
'ang'

>>> fruit[:5]
'Mango'

>>> fruit[5:]
'steen'
```

String methods:

Method Description:

| Method         | Description                                                                                   |
| -------------- | :-------------------------------------------------------------------------------------------- |
| capitalize()   | Converts the first character to upper case                                                    |
| casefold()     | Converts string into lower case                                                               |
| center()       | Returns a centered string                                                                     |
| count()        | Returns the number of times a specified value occurs in a string                              |
| encode()       | Returns an encoded version of the string                                                      |
| endswith()     | Returns true if the string ends with the specified value                                      |
| expandtabs()   | Sets the tab size of the string                                                               |
| find()         | Searches the string for a specified value and returns the position of where it was found      |
| format()       | Formats specified values in a string                                                          |
| format_map()   | Formats specified values in a string                                                          |
| index()        | Searches the string for a specified value and returns the position of where it was found      |
| isalnum()      | Returns True if all characters in the string are alphanumeric                                 |
| isalpha()      | Returns True if all characters in the string are in the alphabet                              |
| isascii()      | Returns True if all characters in the string are ascii characters                             |
| isdecimal()    | Returns True if all characters in the string are decimals                                     |
| isdigit()      | Returns True if all characters in the string are digits                                       |
| isidentifier() | Returns True if the string is an identifier                                                   |
| islower()      | Returns True if all characters in the string are lower case                                   |
| isnumeric()    | Returns True if all characters in the string are numeric                                      |
| isprintable()  | Returns True if all characters in the string are printable                                    |
| isspace()      | Returns True if all characters in the string are whitespaces                                  |
| istitle()      | Returns True if the string follows the rules of a title                                       |
| isupper()      | Returns True if all characters in the string are upper case                                   |
| join()         | Converts the elements of an iterable into a string                                            |
| ljust()        | Returns a left justified version of the string                                                |
| lower()        | Converts a string into lower case                                                             |
| lstrip()       | Returns a left trim version of the string                                                     |
| maketrans()    | Returns a translation table to be used in translations                                        |
| partition()    | Returns a tuple where the string is parted into three parts                                   |
| replace()      | Returns a string where a specified value is replaced with a specified value                   |
| rfind()        | Searches the string for a specified value and returns the last position of where it was found |
| rindex()       | Searches the string for a specified value and returns the last position of where it was found |
| rjust()        | Returns a right justified version of the string                                               |
| rpartition()   | Returns a tuple where the string is parted into three parts                                   |
| rsplit()       | Splits the string at the specified separator, and returns a list                              |
| rstrip()       | Returns a right trim version of the string                                                    |
| split()        | Splits the string at the specified separator, and returns a list                              |
| splitlines()   | Splits the string at line breaks and returns a list                                           |
| startswith()   | Returns true if the string starts with the specified value                                    |
| strip()        | Returns a trimmed version of the string                                                       |
| swapcase()     | Swaps cases, lower case becomes upper case and vice versa                                     |
| title()        | Converts the first character of each word to upper case                                       |
| translate()    | Returns a translated string                                                                   |
| upper()        | Converts a string into upper case                                                             |
| zfill()        | Fills the string with a specified number of 0 values at the beginning                         |
