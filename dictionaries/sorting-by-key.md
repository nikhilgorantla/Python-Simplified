# Sorting by Key

Dictionaries are unordered. Dictionary items may be displayed in key order by sorting a list of keys using the sorted\(\) function and the dictionary.keys\(\) method.

```
dictionary = {
    'cat': 'Frisky',
    'dog': 'Spot',
    'fish': 'Bubbles',
}

for key in sorted(dictionary.keys()):
    print("dictionary[%s]: %s" % (key, dictionary[key]))
    
    
Output:

dictionary[cat]: Frisky
dictionary[dog]: Spot
dictionary[fish]: Bubbles
```



