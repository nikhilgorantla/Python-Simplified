# Multidimensional

Multi dimensional lists are lists within lists.

```
table = [[1, 2, 3], [4, 5, 6], [7, 8, 9]]

for row in range(len(table)):
    for column in range(len(table[row])):
        print(table[row][column], end = '\t')
    print()
    
    
Output:

1       2       3
4       5       6
7       8       9
```



