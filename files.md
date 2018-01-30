# The os.remove\(\) Method

The os.remove\(\) method removes \(deletes\) the given file.

```
import os

path = os.getcwd()
filename2 = os.path.join(path, "__python_demo2.tmp")
if not os.path.isfile(filename2):
    raise Exception("File doesn't exist. Can't continue.")

os.remove(filename2)
if not os.path.isfile(filename2):
    print("Removed %s" % filename2)
```

Output:

```
Removed /home/ubuntu/workspace/__python_demo2.tmp
```



