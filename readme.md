Fillygons
=========

This repository contains precompiled [fillygon](http://fillygons.feuermurmel.ch/) geometries
as _STL_ files. There are (at the moment) three different top-level directories, each containing
36 distinct geometric models like triangles, squares, hexagons, various rhombi etc.

Each geometric model exists in four specific flavours: normal (just the frame),
with the area filled, with corners, and filled with corners.

In total, this repository contains 432 ready-made _STL_ files for 3D printing.
Recompilation of all [OpenScad](http://www.openscad.org/) fillygon
[source files](https://github.com/Fillygons/fillygons) takes several hours.


Hints for slicing
-----------------

Slicing the _STL_ files to generate the printer-specific _G-code_ representation
suitable for your 3D printer at hand is a standard process.
The [Cura](https://ultimaker.com/en/products/cura-software) software does a great
job here, its use is straight-forward.


Hints for printing
------------------

Try the `0.25mm` files first. If the hinges are too tight or loose,
try `0.4mm` or `0.20mm` files. Which version works best can also vary
across the exact kind of filament used.
