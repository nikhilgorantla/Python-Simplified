# The compile\(\) Method

The compile\(\) method compiles a regular expression pattern into a regular expression object, which can be used for matching using its match\(\) and search\(\) methods. The expression’s behaviour can be modified by specifying a flags value.

```
import re

string = "<p>Lines of<BR>HTML text</p>"
regex = re.compile("<br>", re.IGNORECASE)
match = regex.search(string)
if match:
    print("start:", match.start(0))
    print("end:", match.end(0))
    print("group:", match.group(0))
    
    
    
Output:

start: 11
end: 15
group: <BR>
```



