# The os.chdir\(\) Method

The os.chdir\(\) method changes the current working directory to the given path.

```
import os

directory = os.getcwd()
print("Current working directory:", directory)
os.chdir("..")
print("Changed to:", os.getcwd())
os.chdir(directory)
print("Changed back to:", directory)
```

Output:

```
Current working directory: /home/ubuntu/workspace
Changed to: /home/ubuntu
Changed back to: /home/ubuntu/workspace
```



