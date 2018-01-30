# Greedy vs. Non-greedy

The '\*', '+', and '?' quantifiers are all greedy; they match as much text as possible. Adding ? after the quantifier makes it perform the match in non-greedy or minimal fashion; as few characters as possible will be matched.

```
import re

string = "<h1>Heading</h1><p>HTML text.</p>"

match = re.search("<.*>", string)
if match:
    print("Greedy")
    print("start:", match.start(0))
    print("end:", match.end(0))
    print("group:", match.group(0))

match = re.search("<.*?>", string)
if match:
    print("\nNon-greedy")
    print("start:", match.start(0))
    print("end:", match.end(0))
    print("group:", match.group(0))
    
    
Output:

Greedy
start: 0
end: 33
group: <h1>Heading</h1><p>HTML text.</p>

Non-greedy
start: 0
end: 4
group: <h1>
```



