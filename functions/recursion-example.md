# Recursion Example

The factorial of a non-negative integer n, denoted by n!, is the product of all positive integers less than or equal to n.

```
def factorial(value):
    """This function returns the factorial of the value provided using recursion."""

    if type(value) is not int:
        raise TypeError("Parameter value must be an integer.")

    if value < 0:
        result = 0
    elif value == 0:
        result = 1
    else:
        result = value * factorial(value - 1)
    return result

print("5! =", factorial(5))



Output:

5! = 120
```



