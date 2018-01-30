# Nonlocal Variables

The nonlocal statement causes the listed identifiers to refer to previously bound variables in the nearest enclosing scope excluding globals

```
global_value = 1

def function():
    function_value = 2
    
    def nested_function():
        global global_value
        nonlocal function_value
        
        global_value = 3
        function_value = 4
    
    nested_function()
    print("Global value:", global_value)
    print("Function value:", function_value)

function()


Output:

Global value: 3
Function value: 4
```



