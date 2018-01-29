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



