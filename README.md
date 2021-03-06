Blender Curve CAD Tools
=======================

2015/12/07 - Trim Tool is up !

_______________________


inspired by [zeffii's work] (https://github.com/zeffii) I've tried to adapt the Extend/Trim functions for Bezier Curves.
This test version is absolutely NOT bug-free and there are a couple of restrictions, too:

- we're talking about `Bezier` Spline, not `Poly`, neither `NURBS`
- even if applicable to 2D and 3D Shapes, these functions work within a 2D space
- all concerned splines must be in the same curve object

Also note that 100% precision can never be achieved, since Bezier Splines themselves are just an approximation of a mathematical paradigm. I hope it will be close enough for most purposes, though.

#Extend

Extend Tool has two modes:

One selected endpoint:

![Imgur](http://i.imgur.com/zd2TXcy.png)

The selected point is extended to the next line in space blocking its way.


Two selected endpoints:

![Imgur](http://i.imgur.com/srN4u93.png)

Both splines are projected in space to their meeting point.

#Trim

Simply select a point on a segment you want to trim:

![Imgur](http://i.imgur.com/r6Byfvq.png)

And voilà !
