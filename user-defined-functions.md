# User-Defined Functions

A function definition defines a user-defined function object.If specified, return leaves the current function call with the expression list \(or None\) as return value.

```
def function_1():
    print("In function_1")
    
def function_2(parameter):
    print("In function_2 with parameter value:", parameter)
    
def function_3(parameter):
    print("In function_3 with parameter value:", parameter)
    return(parameter * 2)
    
function_1()
function_2("test")
result = function_3("test")
print("function_3 returned", result)



Output:
In function_1
In function_2 with parameter value: test
In function_3 with parameter value: test
function_3 returned testtest
```



