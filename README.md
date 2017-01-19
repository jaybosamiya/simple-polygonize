# Simple Polygonize

Demonstration of algorithm for finding a simple polygon that passes through given points.

Implemented for CSN-523 (Computational Geometry) course assignment

## Algorithm

1. Choose a suitable reference point (I used arithmetic mean of each axis)
2. Calculate angle of line segment joining each given point to the reference point, with respect to the X axis
3. Sort the points based upon the angle of incidence calculated above
4. Join adjacent points in the sorted order using line segments
5. Join first and last point with a line segment

## How to run

Simply run the `simply-polygonize.py` file using `python simply-polygonize.py` or `python simply-polygonize.py {N}`, where `N` is the number of points required.

When the program runs, it will prompt with the help text:

```
+/- Change N
 r  randomize points
 q  quit
```

Press any of the above keys to do the corresponding action.

## Demonstration

Click on the Youtube video thumbnail below to see the program in action

[![Demo](https://img.youtube.com/vi/WXUb6b_7CIk/0.jpg)](https://www.youtube.com/watch?v=WXUb6b_7CIk)

## License

All parts of this repository are covered under the [MIT License](https://jay.mit-license.org/2017)
