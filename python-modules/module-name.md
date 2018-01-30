# Module Name

When modules are imported, the \_\_name\_\_ variable is set to the name of the module. When the Python interpreter runs a module directly, the \_\_name\_\_ variable is set to "\_\_main\_\_". This allows a module designed to be imported to add a main\(\) function that will only execute when the module is run directly.



```
def main():
    """Used to demonstrate and/or test module code."""
    ...

if __name__ == "__main__":
    main()
```

### The dir\(\) Function

The dir\(\) function returns the list of names in the current local scope, or for the object, if specified.

```
print(dir())
```



