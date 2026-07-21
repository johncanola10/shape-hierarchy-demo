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

## Files

- `Shape.java` defines the abstract base type
- `Sphere.java`, `Cylinder.java`, and `Cone.java` implement concrete shapes
- `ShapeArray.java` creates the objects and prints them through a polymorphic array

## Notes

This is one of the cleaner Java examples from the coursework bundle because the intent is obvious and the class relationships are easy to follow.
