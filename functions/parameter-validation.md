# Parameter Validation

According to the Zen of Python, errors should never pass silently.Parameter validation is automated processing to validate the spelling or accuracy of parameters passed to a function or module.

```
def function(integer):
    if type(integer) is not int:
        raise TypeError("Parameter integer must be an integer.")

    if integer < 0:
        raise ValueError("Parameter integer must be greater than or equal to zero.")
    ...
```



