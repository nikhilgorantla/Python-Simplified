# Except Statement

A try statement may have more than one except clause, to specify handlers for different exceptions

```
try:
    value = input("Enter a numeric value: ")
    result = 1 / float(value)
    print("1 / " + value + " = " + str(result))
except ValueError as error:
    print(value + " is not a numeric value!")
except ZeroDivisionError as error:
    print("Cannot divide by 0!")
except:
    print("An unexpected error occurred dividing 1 by " + value + "!")
```



