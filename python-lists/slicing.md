# Slicing

Lists may be sliced.

```
list = [1, 2, 3, 4, 5]

list = list[0:2] + list[3:]
for i in range(len(list)):
    print("list[%d]: %d" % (i, list[i]))
    
    
Output:

list[0]: 1
list[1]: 2
list[2]: 4
list[3]: 5
```



