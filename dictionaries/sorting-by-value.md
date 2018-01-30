# Sorting by Value

Dictionaries are unordered. Dictionary items may be displayed in value order by sorting a list of key-value pairs using the sorted\(\) function and the dictionary.get\(\) method.

```
dictionary = {
    'cat': 'Frisky',
    'dog': 'Spot',
    'fish': 'Bubbles',
}

for key in sorted(dictionary, key=dictionary.get):
    print("dictionary[%s]: %s" % (key, dictionary[key]))
    
    
Output:

dictionary[fish]: Bubbles
dictionary[cat]: Frisky
dictionary[dog]: Spot
```



