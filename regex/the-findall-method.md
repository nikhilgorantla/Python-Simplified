# The findall\(\) Method

The findall\(\) method matches all occurrences of the given regular expression in the string and returns a list of matching strings.

```
import re

string = "<h1>Heading</h1><p>HTML text.</p>"
matches = re.findall("<.*?>", string)
print("matches:", matches)


Output:

matches: ['<h1>', '</h1>', '<p>', '</p>']
```



