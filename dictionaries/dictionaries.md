# Dictionaries

Dictionaries are collections that are indexed by keys, which can be any immutable type. It is best to think of a dictionary as an unordered set of key: value pairs, with the requirement that the keys are unique \(within one dictionary\). Placing a comma-separated list of key:value pairs within braces adds initial key:value pairs to the dictionary.

```
dictionary = {
    'cat': 'Frisky',
    'dog': 'Spot',
    'fish': 'Bubbles',
}

print("dictionary:", dictionary)
print("dictionary['cat']:", dictionary['cat'])
print("dictionary['dog']:", dictionary['dog'])
print("dictionary['fish']:", dictionary['fish'])


Output:

dictionary: {'dog': 'Spot', 'fish': 'Bubbles', 'cat': 'Frisky'}
dictionary['cat']: Frisky
dictionary['dog']: Spot
dictionary['fish']: Bubbles
```



