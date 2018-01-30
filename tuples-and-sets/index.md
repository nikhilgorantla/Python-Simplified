# Index

List and tuple items may be accessed by index. Dictionary items are accessed by key. Set items cannot be accessed by index.

```
list = [1, 2, 3]
dictionary = {1: "one", 2: "two", 3: "three"}
tuple = (1, 2, 3)
set = {1, 2, 3}

for i in range(len(list)):
    print("list[%d]: %d" % (i, list[i]))
print()

for key in dictionary:
    print("dictionary[%s]: %s" % (key, dictionary[key]))
print()

for i in range(len(tuple)):
    print("tuple[%d]: %d" % (i, tuple[i]))
print()

try:
    for i in range(len(set)):
        print("set[%d]: %d" % (i, set[i]))
except Exception as exception:
    print(exception)
    
    
Output:

list[0]: 1
list[1]: 2
list[2]: 3

dictionary[1]: one
dictionary[2]: two
dictionary[3]: three

tuple[0]: 1
tuple[1]: 2
tuple[2]: 3

'set' object does not support indexing
```



