# The file.read\(\) Method

The file.read\(\) method reads the given number of bytes from the file, or all content if no size is given, and returns the bytes that were read.

```
import os

path = os.getcwd()
filename = os.path.join(path, "__python_demo.tmp")
if os.path.isfile(filename):
    file = open(filename, "r")
    text = file.read()
    file.close()
    print("File text:", text)
```

Output:

```
File text: Temporary Python Demo File
```



