# Day 2 Project : TIP CALCULATOR 

## Python Primitive Data Types

### String
Strings are sequences of characters enclosed in quotes (`'` or `"`). They are used to represent text data.

```python
"Hello"[0]
print("Hello"[0])

"Hello"[4]
print("123" + "345")
```

#### Subscript
Subscripting allows you to access individual characters in a string using their index, like `my_string[0]` for the first character.

### Integer
Integers are whole numbers that can be both positive and negative. They are often used for counting or iteration.

```python

print(123 = 345)

```

#### Large Integers
Python automatically handles large integers, allowing for integer values that exceed the usual 32- or 64-bit size limitations.

```python

123_456_789

#Computers just ignores the "_" and interprets as 123456789 

```

### Float
Floats represent real numbers and are written with a decimal point. They are used for more precise numerical calculations.

```python

3.14159

```
#### Floating Point Number
Floating-point numbers in Python are approximations due to the limitations of binary representation, which can lead to rounding errors.

```python 

3141.59

```

### Boolean
Booleans represent the truth values `True` and `False`. They are often used for conditional statements and logic operations. There are no quotations for True or False in the code. Always begins with a Capital letter. Very oftenly used in the code.

```python

True
False

```

#### Type Error
A Type Error occurs when an operation is performed on an inappropriate data type, like trying to concatenate a string with an integer in Python.

### Type Checking
Type checking involves verifying the data types of variables before performing operations on them. This can be done statically before runtime or dynamically during execution.

### Type Conversion
Type conversion, also known as type casting, is the process of converting a variable from one data type to another, such as converting an integer to a string with Python's `str()` function.

### Mathematical Operations

Mathematical operations involve calculations using arithmetic operators such as addition (+), subtraction (-), multiplication (*), division (/), and exponentiation (**). The order of operations is determined by the PEMDASLR acronym, which stands for Parentheses, Exponents, Multiplication and Division (from left to right), and Addition and Subtraction (from left to right).

```python 

3 + 5
7 - 4
3 * 2
6 / 3
2 ** 3

PEMDASLR

()  (Parentesis)
**  (Exponents)
* / (Multiplication and Division)
+ - (Addition and Subtraction)

print(3 * 3 + 3 / 3 - 3)



print (6 / 3)

print(type(6 / 3)) #Insert Type to check the type of data type)

# In Python, in division it always gives a float.

print(2 ** 3)

```
### Number Manipulation and F Strings in Python 

Number manipulation refers to manipulating numerical values in various ways, including performing calculations, converting between different data types (like int and float), and rounding numbers using functions like int(), round(), and // for floor division. F-strings in Python are a way to format strings that allows you to embed expressions, variables, and values directly within the string using curly braces {} preceded by an 'f'.

```python 

print(8 / 3)

print(int(8 / 3))

print(round(8 / 3))

print(round(8 / 3, 2))

print(round(2.6666666, 2))

print( 8 // 3)

print(type(8 // 3))

print(type(8 / 3))

print(4 / 2)

result = 4 / 2 
result / = 2 

print(result)


score = 0 


# User scores a point 

score  += 1

score -= 1 

print(score)

```

### F Strings

```python 

score = 0 
height = 1.8 
isWinning = True

# F String - All in one using F Sting in the front and using Curly Braces

print(f"your score is {score}, your height is {height}, you are winning is {isWinning}")


```