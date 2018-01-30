# The os.walk\(\) Method

The os.walk\(\) method generates the subdirectories and files in a given path as a 3-tuple of a path string with subdirectory list and filename list.

```
import os

for path, directories, files in os.walk(os.getcwd()):
    for directory in directories:
        print(os.path.join(path, directory))
    for file in files:
        print(os.path.join(path, file))
```

Output:

```
... <all subdirectories and files in the current working directory>
```



