# Stacks and Queues

The list.pop\(\[i\]\) method removes the item at the given position in the list, and returns it. If no index is specified, pop\(\) removes and returns the last item in the list.This allows for simple stack \(last-in, first-out\) and queue \(first-in, first-out\) processing.

```
print("Stack: Last in, first out")
list = []
list.append(1)
list.append(2)
list.append(3)
while len(list) > 0:
    print(list.pop())

print("\nQueue: First in, first out")
list = []
list.append(1)
list.append(2)
list.append(3)
while len(list) > 0:
    print(list.pop(0))
    
    
    
Output:

Stack: Last in, first out
3
2
1

Queue: First in, first out
1
2
3
```



