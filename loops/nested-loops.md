# Nested Loops

Loops may be nested with one loop inside another.

```
for i in range(1, 4):
    for j in range(1, 4):
        print(str(i) + str(j), end = '\t')
    print()
print()

i = 1
while i < 4:
    j = 1
    while j < 4:
        print(str(i) + str(j), end = '\t')
        j += 1
    print()
    i += 1


Output:

11      12      13
21      22      23
31      32      33

11      12      13
21      22      23
31      32      33

```

# 



