# **Input Function** {#input-function-------------}

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



