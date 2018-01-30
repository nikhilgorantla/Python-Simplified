# Python Strings

Textual data in Python is handled with str objects, or strings. Strings are immutable sequences of Unicode code points.

```
string = "Test"

print("Characters:")
for letter in string:
    print(letter)

print("\nCharacters by position:")
for i in range(len(string)):
    print("string[%d]: %c" % (i, string[i]))


Output:

Characters:
T
e
s
t

Characters by position:
string[0]: T
string[1]: e
string[2]: s
string[3]: t
```



