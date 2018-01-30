# Variable Named Arguments

Variable named arguments may be accessed using the \*\* operator.The variable named arguments are provided as a Python dictionary

```
def keywords(**kwargs):
    for item in kwargs.items():
        print(item)

keywords(x = 1, y = 2)


Output:

('y', 2)
('x', 1)
```



