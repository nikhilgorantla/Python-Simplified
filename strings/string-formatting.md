# String Formatting

String objects have one unique built-in operation: the % operator \(modulo\). This is also known as the string formatting or interpolation operator. Given format % values \(where format is a string\), % conversion specifications in format are replaced with zero or more elements of values.

```
print("Value:", value)
print("Integer: %i" % value)
print("Octal: %o" % value)
print("Hexadecimal: %x" % value)
print("Float: %.2f" % value)
print("Exponent: %.2e" % value)
print("Character: %c" % value)
print("String: %s" % value)
print("Multiple: %i, %o, %x, %.2f, %.2e, %c, %s" % 
    (value, value, value, value, value, value, value))

    
Output: 

Value: 65.5
Integer: 65
Octal: 101
Hexadecimal: 41
Float: 65.50
Exponent: 6.55e+01
Character: A
String: 65.5
Multiple: 65, 101, 41, 65.50, 6.55e+01, A, 65.5    

```



