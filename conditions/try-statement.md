# Try Statement

The try statement executes the try clause. If no exception occurs, the except clause is skipped. If an exception occurs during execution of the try clause, the except clause is executed, and then execution continues after the try statement.

```
try:
    value = input("Enter a numeric value: ")
    result = 1 / float(value)
    print("1 / " + value + " = " + str(result))
except:
    print("An error occurred dividing 1 by " + value + "!")
```



