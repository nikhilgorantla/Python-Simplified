# Class Example

The following example creates a class named Shape with an attribute named sides and a method named perimeter. Three instances of the class are created, one each for a triangle, rectangle, and square. The attribute value and method result are printed for each shape.

```
class Shape(object):
    sides = None

    def __init__(self, sides):
        self.sides = sides

    def perimeter(self):
        perimeter = 0
        for side in self.sides:
            perimeter += side
        return perimeter

triangle = Shape([3, 4, 5])
print("triangle sides:", triangle.sides)
print("triangle perimeter:", triangle.perimeter())

rectangle = Shape([4, 2, 4, 2])
print("rectangle sides:", rectangle.sides)
print("rectangle perimeter:", rectangle.perimeter())

square = Shape([2, 2, 2, 2])
print("square sides:", square.sides)
print("square perimeter:", square.perimeter())


Output:

triangle sides: [3, 4, 5]
triangle perimeter: 12
rectangle sides: [4, 2, 4, 2]
rectangle perimeter: 12
square sides: [2, 2, 2, 2]
square perimeter: 8
```



