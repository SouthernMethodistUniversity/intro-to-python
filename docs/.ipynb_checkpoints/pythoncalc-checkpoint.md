# Python - Calculator

Python is a popular programming language for tasks such as data collection, cleaning, and analysis.



## Using Python as a Calculator

First, we will gain some experience using Python for its most basic functionality, calculating!

### Basic Calculations

You can add, subtract, divide, and multiply using the same symbols you would on a graphing calculator

```
(1 + 1) / 4
(3 * 10) - 5
2 ** 3   # Exponentiation
```

### Boolean Comparisons

You can evaluate boolean expressions, which return either `TRUE` or `FALSE`. The `>`, `<`, `>=`, `<=`, `==`, `&`, and `|` operators are all valid.

```
1 == 1
2 < 1
```
Logical operators: The `&` and `|` operators are the AND and OR logical operators. The `&` operator evaluates to `TRUE` only if both sides of an expression are `TRUE`.

```
(1 == 1) and (2 < 1)   # AND
(1 == 1) or (2 < 1)    # OR
```

## Assigning Variables

You can assign a variable in Python using either the  `=` operator. A variable is a name that stores an object. Variable names should start with a letter or underscore and can include letters, numbers, and underscores. The only limitation to variable names is that you cannot start with a number. 

``` 
x = 2
print(x)

y = 3
z = x + y
print(z)

```

## Comments

As in most programming languages, you have the ability to add comments to your code. In Python, the `#` symbol tells Python to ignore everything after it. You can use comments to explain what is happening in your code so that you or someone else can read your really complex code a year later without too much effort. Comments are used throughout the code in this workshop to help you understand what each line does.

```
# This is a comment
z = 3  # This is also a comment
print(z)

```

As you can see, the comment did not interfere with setting the variable `z`. Comments are ignored when the code runs.

## Intro to Functions

A function is an object that takes arguments, processes them, and outputs whatever it calculated. Python has a variety of built-in functions, but you can also build your own.  An example of a built-in function in Python Example: Python’s pow() function raises a number to a power:

```
pow(2, 3)   # 2^3 = 8

```

You can also define your own:
```
def square(x):
    return x * x

square(4)  # Output: 16
```
Python has many built-in functions (like len(), print(), sum()), and you’ll learn to write your own as you go.

