# Mutability

List and dictionary items are mutable. Tuple and set items are immutable

```
list = [1, 2, 3]
dictionary = {1: "one", 2: "two", 3: "three"}
tuple = (1, 2, 3)
set = {1, 2, 3}

list[0] = 0
print("list: mutable")

dictionary[1] = "zero"
print("dictionary: mutable")

try:
    tuple[0] = 0
    print("tuple: mutable")
except:
    print("tuple: immutable")

try:
    set[0] = 0
    print("set: mutable")
except:
    print("set: immutable")

print()
print("list:", list)
print("dictionary:", dictionary)
print("tuple:", tuple)
print("set:", set)


Output:

list: mutable
dictionary: mutable
tuple: immutable
set: immutable

list: [0, 2, 3]
dictionary: {1: 'zero', 2: 'two', 3: 'three'}
tuple: (1, 2, 3)
set: {1, 2, 3}
```



