# The os.path.isdir\(\) Method

The os.path.isdir\(\) method returns True if the given path is an existing directory.

```
import os

path = os.getcwd()
if os.path.isdir(path):
    print("Current working directory exists.")
else:
    print("Current working directory does not exist.")
```

Output

```
Current working directory exists.
```



