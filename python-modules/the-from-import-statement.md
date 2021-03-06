# The from ... import Statement

The from...import statement finds a module, loads it, initializes it if necessary, and then adds module references to the local namespace, allowing functions and classes to be accessed without a module reference.Use of import rather than from...import is preferred. While from ... import supports an \* option to import all references rather than naming specific functions or classes, this use is discouraged.

```
from functions import function1
from classes import Class1

function1()

class1 = Class1()
class1.method1()

Output:

In function1
In method1
```



