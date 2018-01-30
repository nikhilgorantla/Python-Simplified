# The sys.argv Property

The sys.argv property returns the list of command line arguments passed to a Python script. argv\[0\] is the script name.

```
import sys

for i in range(0, len(sys.argv)):
    print("sys.argv[%d]: %s" % (i, sys.argv[i]))
```

Output:

```
sys.argv[0]: /home/ubuntu/workspace/argv.py
sys.argv[1]: test1
sys.argv[2]: test2
```



