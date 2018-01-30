# Reading Lines

For reading lines from a file, you can loop over the file object. This is memory efficient, fast, and leads to simple code.

```
import os

path = os.getcwd()
filename = os.path.join(path, "__python_demo.tmp")
file = open(filename, "r")
for line in file:
    print(line, end='')
file.close()
```

Output:

```
Temporary Python Demo File
```



