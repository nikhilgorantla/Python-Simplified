# Parameters

A parameter is a named entity in a function definition that specifies an argument that the function can accept.Functions may specify a default value for one or more arguments.Functions may also be called using keyword arguments rather than positional arguments

```
def parameters(x = 1, y = 2):
    print("x =", x, "y =", y)
    
parameters()
parameters(3, 4)
parameters(5, 6)
parameters(y = 7, x = 8)


Output:

x = 1 y = 2
x = 3 y = 4
x = 5 y = 6
x = 8 y = 7
```



