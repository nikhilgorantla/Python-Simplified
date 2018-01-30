# Local Variables

If a variable is assigned a value anywhere within the function’s body, it’s assumed to be a local unless explicitly declared as global.

```
def local_variable():
    value = 1
    print("Local value:", value)

def local_parameter(value):
    print("Parameter value:", value)
    value = 2
    print("Parameter value:", value)

local_variable()
try:
    print("value:", value)
except:
    print("Cannot access local variable.")
    
value = 1
local_parameter(value)
print("Global value:", value)



Output:

Local value: 1
Cannot access local variable.
Parameter value: 1
Parameter value: 2
Global value: 1
```



