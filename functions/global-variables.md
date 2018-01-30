# Global Variables

Variables that are only referenced inside a function are implicitly global. If a variable is assigned a value anywhere within the function’s body, it’s assumed to be a local unless explicitly declared as global.

```
def global_access():
    print("Global value:", value)

def global_modification():
    global value
    value = 2
    print("Global value:", value)

value = 1
global_access()
global_modification()
print("Global value:", value)



Output:

Global value: 1
Global value: 2
Global value: 2
```

# 



