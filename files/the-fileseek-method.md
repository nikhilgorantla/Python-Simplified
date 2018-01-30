# The file.seek\(\) Method

The file.seek\(\) method moves the file position to the given offset from the given reference point. Reference points are 0 for the beginning of the file, 1 for the current position, and 2 for the end of the file.

```
import os

path = os.getcwd()
filename = os.path.join(path, "__python_demo.tmp")
if os.path.isfile(filename):
    file = open(filename, "a+")
    print("Open file position:", file.tell())
    file.seek(0, 0)
    print("Seek file position:", file.tell())
    text = file.read()
    file.close()
    print("File text:", text)
```

Output:

```
Open file position: 60
Seek file position: 0
File text: Temporary Python Demo File - Appended to the end of the file
```



