# The file.close\(\) Method

The file.close\(\) method closes the file and frees any system resources taken up by the open file.

```
import os

path = os.getcwd()
filename = os.path.join(path, "__python_demo.tmp")
file = open(filename, "w")
file.write("Temporary Python Demo File")
file.close()
if os.path.isfile(filename):
    print("Created %s" % filename)
```

Output:

```
Created /home/ubuntu/workspace/__python_demo.tmp
```



