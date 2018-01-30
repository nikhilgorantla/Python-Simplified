# The split\(\) Method

The split\(\) method splits string by the occurrences of pattern.

```
import re

string = "cat: Frisky, dog: Spot, fish: Bubbles"
keys = re.split(": ?\w*,? ?", string)
values = re.split(",? ?\w*: ?", string)
print("string:", string)
print("keys:", keys)
print("values:", values)


Output:


string: cat: Frisky, dog: Spot, fish: Bubbles
keys: ['cat', 'dog', 'fish', '']
values: ['', 'Frisky', 'Spot', 'Bubbles']
```



