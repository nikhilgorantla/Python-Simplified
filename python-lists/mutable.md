# Mutable

List items are mutable, i.e. it is possible to change their content.

```
list = [1, 2, 3]

for i in range(len(list)):
    list[i] = -list[i]
    print("list[%d]: %d" % (i, list[i]))
    
    
Output:

list[0]: -1
list[1]: -2
list[2]: -3
```



