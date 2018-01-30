# The search\(\) Method

The search\(\) method scans for the first match of the given regular expression in the given string and returns a match object if found, or None if there is no match.

```
import re

string = "<h1>Heading</h1><p>HTML text.</p>"
match = re.search("<p>.*</p>", string)
if match:
    print("start:", match.start(0))
    print("end:", match.end(0))
    print("group:", match.group(0))
    
    
Output:

start: 16
end: 33
group: <p>HTML text.</p>
```



