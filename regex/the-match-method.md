# The match\(\) Method

The match\(\) method looks for zero or more characters at the beginning of the given string that match the given regular expression and returns a match object if found, or None if there is no match.

```
import re

string = "<p>HTML text.</p>"
match = re.match("<p>.*</p>", string)
if match:
    print("start:", match.start(0))
    print("end:", match.end(0))
    print("group:", match.group(0))
    
Output:

start: 0
end: 17
group: <p>HTML text.</p>
```



