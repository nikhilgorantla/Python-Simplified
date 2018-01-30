# String Parsing

Python substrings are referred to as slices. Slices are accessed using the syntax`string[start:end]`, with the first character index starting at zero. The slice will include the characters from start up to but not including end. If end is omitted, the slice will include the characters from start through the end of the string. String slices may use negative indexing, in which case the index counts backwards from the end of the string.The find\(\) method returns the lowest index in the string where a substring is found within the given slice. Returns -1 if the substring is not found.

```
string = "Python Programming/Strings"
index = string.find("/")

if index >= 0:
    project = string[0:index]
    page = string[index + 1:]

    print("Project:", project)
    print("Page:", page)
    
Output:

Project: Python Programming
Page: Strings
```



