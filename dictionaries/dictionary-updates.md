# Dictionary Updates

A pair of braces creates an empty dictionary: {}. Dictionary items may be added, updated, and deleted by key.

```
dictionary = {}
dictionary['cat'] = 'Frisky'
dictionary['dog'] = 'Spot'
dictionary['fish'] = 'Bubbles'
print("dictionary:", dictionary)

dictionary['dog'] = 'Rover'
print("dictionary:", dictionary)

del dictionary['fish']
print("dictionary:", dictionary)


Output:

dictionary: {'cat': 'Frisky', 'fish': 'Bubbles', 'dog': 'Spot'}
dictionary: {'cat': 'Frisky', 'fish': 'Bubbles', 'dog': 'Rover'}
dictionary: {'cat': 'Frisky', 'dog': 'Rover'}
```



