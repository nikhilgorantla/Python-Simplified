# **Data Types  **

Built-in Python data types include integer \(int\), floating point \(float\), string \(str\), and Boolean \(bool\) data types.

```
value = 1 + 1
print(value)          # Displays 2
print(type(value))    # Displays <type 'int'>

value = 0.1 + 0.1
print(value)          # Displays 0.2 
print(type(value))    # Displays <type 'float'>

value = '1' + '1'
print(value)          # Displays 11
print(type(value))    # Displays <type 'str'>

value = True
print(value)          # Displays True
print(type(value))    # Displays <type 'bool'>
```



**Quotes      
**

String literals are written in a variety of ways, including single quotes, double quotes, and triple quotes. Triple quoted strings may span multiple lines.\[4\] The backslash \(\\) character is used to escape characters that otherwise have a special meaning, such as newline, backslash itself, or the quote character.

```
value = 'single quotes'
print(value)

value = "double quotes"
print(value)

value = \
'''triple quotes
    span multiple lines'''
print(value)

value = '"nested quotes"'
print(value)

value = "'nested quotes'"
print(value)

value = "\"escape character quotes\nand multiple lines\""
print(value)
```

**Numeric Operations      
**

All numeric types \(except complex\) support the following operations, sorted by ascending priority.

```
a = 3
b = 2

print(a + b)     # 5
print(a - b)     # 1
print(a * b)     # 6
print(a / b)     # 1.5
print(a // b)    # 1
print(a % b)     # 1
print(-a)        # -3
print(a ** b)    # 9
```

**Assignment Operations      
**

An assignment statement evaluates the expression and assigns the result to the target. Augmented assignment is the combination, in a single statement, of an operation and an assignment statement.

```
a = 3
b = 2

a += b    # a = 5
a -= b    # a = 3
a *= b    # a = 6
a /= b    # a = 3.0
a //= b   # a = 0.0
a %= b    # a = 1.0
a **= b   # a = 1.0
```

**Input Function      
**

Python 2: If the prompt argument is present, it is written to standard output without a trailing newline. The function then reads a line from input, converts it to a string \(stripping a trailing newline\), which is then parsed and evaluated as a Python expression.

Python 3: If the prompt argument is present, it is written to standard output without a trailing newline. The function then reads a line from input, converts it to a string \(stripping a trailing newline\), and returns that.

```
input([prompt])

#Python 2
value = input("Enter a numeric value: ")
print("You entered " + str(value))

value = input('Enter a string value in "quotes": ')
print("You entered " + value)

#Python 3
value = input("Enter a value: ")
print("You entered a string value " + value)
```



