# Bitwise Operations

Bitwise operations only make sense for integers. Negative numbers are treated as their 2’s complement value.

```
a = 5
b = 3

print(bin(a))        # 0101
print(bin(b))        # 0011
print(bin(a & b))    # 0001
print(bin(a | b))    # 0111
print(bin(a ^ b))    # 0110
print(bin(~a))       # -0110
print(bin(a << b))   # 101000
print(bin(a >> b))   # 000000
```



