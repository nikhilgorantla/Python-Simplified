# Methods

Lists support a variety of methods, including:

* list.append\(x\) - Adds an item to the end of the list.
* list.insert\(i, x\) - Inserts an item at a given position.
* list.remove\(x\) - Removes the first item from the list whose value is x
* list.reverse\(\) - Reverse the elements of the list in place.
* list.sort\(\) - Sorts the items of the list in place.
* list.clear\(\) - Removes all items from the list.



```
list = []

print("List:", list)

list.append(1)
list.append(2)
print("After append:", list)

list.insert(2, 3)
list.insert(0, 4)
print("After insert:", list)

list.remove(4)
print("After remove:", list)

list.reverse()
print("After reverse:", list)

list.sort()
print("After sort:", list)

list.clear()
print("After clear:", list)



Output:

List: []
After append: [1, 2]
After insert: [4, 1, 2, 3]
After remove: [1, 2, 3]
After reverse: [3, 2, 1]
After sort: [1, 2, 3]
After clear: []


```



