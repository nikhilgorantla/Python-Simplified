# Set Operations

Sets support logical set operations, including membership, subset, superset, union \(\|\), intersection \(&\), and difference \(-\).



```
numbers = {1, 2, 3, 4, 5, 6, 7, 8, 9, 10}
even = {2, 4, 6, 8, 10}
odd = {1, 3, 5, 7, 9}

print("Numbers:", numbers)
print("Even:", even)
print("Odd:", odd)

print("1 in numbers:", 1 in numbers)
print("even.issubset(numbers):", even.issubset(numbers))
print("numbers.issuperset(odd):", numbers.issuperset(odd))
print("even | odd:", even | odd)
print("even & odd:", even & odd)
print("numbers - even:", numbers - even)


Output:

Numbers: {1, 2, 3, 4, 5, 6, 7, 8, 9, 10}
Even: {8, 10, 2, 4, 6}
Odd: {9, 1, 3, 5, 7}
1 in numbers: True
even.issubset(numbers): True
numbers.issuperset(odd): True
even | odd: {1, 2, 3, 4, 5, 6, 7, 8, 9, 10}
even & odd: set()
numbers - even: {1, 9, 3, 5, 7}
```



