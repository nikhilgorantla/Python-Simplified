# **Type Conversion** {#type-conversion}

An object’s type is accessed by the built-in function type\(\).



```
value = 1.9
print(value)          # Displays 1.9
print(type(value))    # Displays <type 'float'>
value = int(value)
print(value)          # Displays 1
print(type(value))    # Displays <type 'int'>

value = 1
print(value)          # Displays 1
print(type(value))    # Displays <type 'int'>
value = float(value)  
print(value)          # Displays 1.0
print(type(value))    # Displays <type 'float'>

value = 1
print(value)          # Displays 1
print(type(value))    # Displays <type 'int'>
value = str(value)  
print(value)          # Displays 1
print(type(value))    # Displays <type 'str'>
```



