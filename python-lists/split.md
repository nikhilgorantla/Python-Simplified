# Split

The string split\(&lt;separator&gt;\) method returns a list of the words in the string, using separator as the delimiter string. If separator is not specified, runs of consecutive whitespace are regarded as a single separator.



```
string = "This is a test"
list = string.split()
print(list)

string = "So-is-this"
list = string.split("-")
print(list)



Output:

['This', 'is', 'a', 'test']
['So', 'is', 'this']
```



