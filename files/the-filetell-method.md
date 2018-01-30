# The file.tell\(\) Method

The file.tell\(\) method returns an integer giving the file object’s current position in the file.

```
import os

path = os.getcwd()
filename = os.path.join(path, "__python_demo.tmp")
if os.path.isfile(filename):
    file = open(filename, "a+")
    print("Open file position:", file.tell())
    file.write(" - Appended to the end of the file")
    print("Write file position:", file.tell())
```

Output:

```
Open file position: 26
Write file position: 60
```



