# If Statement

An if statement may contain zero or more elif parts, and the else part is optional. The keyword ‘elif‘ is short for ‘else if’, and is useful to avoid excessive indentation. An if ... elif ... elif ... sequence is a substitute for the switch or case statements found in other languages.

```
input = input("Is it morning (m), afternoon (a), or evening (e)? ")
if input == "m":
    print("Good morning!")
elif input == "a":
    print("Good afternoon!")
elif input == "e":
    print("Good evening!")
else:
    print("Hello!")
```



