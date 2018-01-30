# The os.mkdir\(\) Method

The os.mkdir\(\) method creates a directory with the given path.

```
import os

path = os.getcwd()

directory = os.path.join(path, "__python_demo__")
if os.path.isdir(directory):
    raise Exception("Path already exists. Can't continue.")
os.mkdir(directory)
```



