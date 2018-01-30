# Membership Comparisons

The operators`in`and`not in`test for membership.`x in s`evaluates to true if x is a member of s, and false otherwise.



```
alphabet = "abcdefghijklmnopqrstuvwxyz"
string = "Python Programming/Strings"

print("The string contains:")
for letter in alphabet:
    if letter in string.lower():
        print(letter)
        
Output: 

The string contains:
a
g
h
i
m
n
o
p
r
s
t
y
```



