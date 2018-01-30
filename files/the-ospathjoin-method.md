# The os.path.join\(\) Method

The os.path.join\(\) method joins one or more path components intelligently, avoiding extra directory separator \(os.sep\) characters.

```
import os

path = os.getcwd()
directory = os.path.join(path, "__python_demo__")
print("path:", path)
print("directory:", directory)
```

Output:

```
path: /home/ubuntu/workspace
directory: /home/ubuntu/workspace/__python_demo__
```



