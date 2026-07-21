# Shape Hierarchy Demo

Java OOP demo showing inheritance and polymorphism across several 3D shapes.

## What It Demonstrates

- abstract base classes
- subclass implementations
- overridden methods
- polymorphic behaviour through a shared `Shape[]`

## Included Shapes

- `Sphere`
- `Cylinder`
- `Cone`

Each shape implements:

- `surface_area()`
- `volume()`
- `toString()`

## Run

```bash
javac Shape.java Sphere.java Cylinder.java Cone.java ShapeArray.java
java ShapeArray
```

## Sample Output

```text
Sphere
Radius: 3.0
Surface Area: 113.09733552923255
Volume: 113.09733552923254

Cylinder
Radius: 2.0
Height: 5.0
Surface Area: 175.92918860102841
Volume: 62.83185307179586

Cone
Radius: 2.0
Height: 4.0
Surface Area: 40.665629538522076
Volume: 16.755160819145562
```

## Files

- `Shape.java` defines the abstract base type
- `Sphere.java`, `Cylinder.java`, and `Cone.java` implement concrete shapes
- `ShapeArray.java` creates the objects and prints them through a polymorphic array

## Notes

This is one of the cleaner Java examples from the coursework bundle because the intent is obvious and the class relationships are easy to follow.
