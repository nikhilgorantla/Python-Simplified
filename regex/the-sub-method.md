# The sub\(\) Method

The sub\(\) method replaces every occurrence of a pattern with a string.

```
import re

string = "<h1>Heading</h1><p>HTML text.</p>"
string = re.sub("<.*?>", "", string)
print("string:", string)

Output

string: HeadingHTML text.
```



