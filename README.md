# Lunar for P5js

### What is Lunar?
Lunar is a lightweight parametric design library for the minimalist, inspired on existing node-based plug-ins for CAD software. She holds algorithms for the easy generation and adaptation of polygon meshes, vectors and list patterns. She has a built-in interactive camera and additional renderer extensions.

### Why use Lunar?
Lunar is meant for architects, designers and artists that don't want to learn multiple, complex, libraries to visualize their three-dimensional concepts. Lunar has all the building blocks for fast sketching in three dimensions. Lunar is compatible for web applications.

### How to work with Lunar?
Lunar groups her algorithms under several classes:
- Vector
  - Vector calculation
  - Vector field generation
- Meshes
  - Mesh generation
- Lists
  - List adaptations
  - Pattern generation
- Render
  - Object drawing
  - Camera

The methods are static and can be called directly from the class. Each method, except the render methods, return an object. To modify an object, you should replace the original with the result of the method.
```
let v = new LVector(0,4,2);
v = Vectors.unitVector(v);
```

---
Dipl.- Ing Boy d'Hont | www.bdhont.net