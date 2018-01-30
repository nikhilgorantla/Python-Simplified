# The os.path.isfile\(\) Method

The os.path.isfile\(\) method returns True if the given path is an existing file.



```
path = os.getcwd()
filename = os.path.join(path, "__python_demo.tmp")
if os.path.isfile(filename):
    print("File exists.")
else:
    print("File does not exist.")
```

Output:

```
File does not exist.
```



