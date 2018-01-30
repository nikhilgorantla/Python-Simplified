# The os.rmdir\(\) Method

The os.rmdir\(\) method removes \(deletes\) the directory with the given path.

```
import os

path = os.getcwd()
directory = os.path.join(path, "__python_demo__")
if os.path.isdir(directory):
    raise Exception("Path already exists. Can't continue.")
os.mkdir(directory)
print("Created directory:", directory)
os.chdir(directory)
print("Changed to:", os.getcwd())
os.chdir(path)
print("Changed back to:", os.getcwd())
os.rmdir(directory)
print("Removed directory:", directory)
```

Output:

```
Created directory: /home/ubuntu/workspace/__python_demo__
Changed to: /home/ubuntu/workspace/__python_demo__
Changed back to: /home/ubuntu/workspace
Removed directory: /home/ubuntu/workspace/__python_demo__
```



