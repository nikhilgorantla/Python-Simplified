# Variable Arguments

Functions may accept a variable number of arguments using the \* operator.The variable arguments are provided as a Python list.

```
def sum(*args):
    total = 0
    for arg in args:
        total += arg
    return total
    
print(sum(1, 2, 3, 4))


Output: 
10
```



