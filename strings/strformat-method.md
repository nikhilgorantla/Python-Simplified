# str.format\(\) Method

The str.format\(\) method uses format strings that contain “replacement fields” surrounded by curly braces {}. Anything that is not contained in braces is considered literal text, which is copied unchanged to the output.

```
integer = 65
float = 65.5
string = "65.5"

print("Decimal: {:d}".format(integer))
print("Binary: {:b}".format(integer))
print("Octal: {:o}".format(integer))
print("Hexadecimal: {:x}".format(integer))
print("Character: {:c}".format(integer))
print("Float: {:.2f}".format(float))
print("Exponent: {:.2e}".format(float))
print("String: {:s}".format(string))
print("Multiple: {:d}, {:b}, {:o}, {:x}, {:c}, {:.2f}, {:.2e}, {:s}".format(
    integer, integer, integer, integer, integer, float, float, string))
    
    

Output:

Decimal: 65
Binary: 1000001
Octal: 101
Hexadecimal: 41
Character: A
Float: 65.50
Exponent: 6.55e+01
String: 65.5
Multiple: 65, 1000001, 101, 41, A, 65.50, 6.55e+01, 65.5
```



