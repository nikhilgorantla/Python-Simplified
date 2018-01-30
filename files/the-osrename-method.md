# The os.rename\(\) Method

The os.rename\(\) method renames the given source file or directory the given destination name.

```
import os

path = os.getcwd()
filename = os.path.join(path, "__python_demo.tmp")
if not os.path.isfile(filename):
    raise Exception("File doesn't exist. Can't continue.")
filename2 = os.path.join(path, "__python_demo2.tmp")
if os.path.isfile(filename2):
    raise Exception("File already exists. Can't continue.")

os.rename(filename, filename2)
if os.path.isfile(filename2):
    print("Renamed %s to %s" % (filename, filename2))
```

Output:

```
Renamed /home/ubuntu/workspace/__python_demo.tmp to /home/ubuntu/workspace/__python_demo2.tmp
```



