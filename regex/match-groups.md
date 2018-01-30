# Match Groups

Match groups match whatever regular expression is inside parentheses, and indicates the start and end of a group; the contents of a group can be retrieved after a match has been performed.



```
import re

string = "<p>HTML text.</p>"
match = re.match("<p>(.*)</p>", string)
if match:
    print("start:", match.start(1))
    print("end:", match.end(1))
    print("group:", match.group(1))

string = "'cat': 'Frisky', 'dog': 'Spot', 'fish': 'Bubbles'"

match = re.search("'cat': '(.*?)', 'dog': '(.*?)', 'fish': '(.*?)'", string)
if match:
    print("groups:", match.group(1), match.group(2), match.group(3))
    
lst = re.findall(r"'(.*?)': '(.*?)',?\s*", string)
for key, value in lst:
  print("%s: %s" % (key, value))
 
```

Output:

```
start: 3
end: 13
group: HTML text.
groups: Frisky Spot Bubbles
cat: Frisky
dog: Spot
fish: Bubbles
```



