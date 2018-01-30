# The open\(\) Function

The open\(\) function opens the given file in the given mode \(read, write, append\) and returns a file object.

```
file = open(filename, "r")    # read
file = open(filename, "w")    # write
file = open(filename, "a")    # append
file = open(filename, "r+")   # read + write
file = open(filename, "w+")   # read + write (new / cleared file)
file = open(filename, "a+")   # read + append (position starts at end of file)
```



