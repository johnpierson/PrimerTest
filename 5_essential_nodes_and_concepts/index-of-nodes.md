# Index of Nodes

This index provides additional information on all the nodes used in this primer, as well as other components you might find useful. This is just an introduction to some of the 500 nodes available in Dynamo.

## Display

### Color

|   |                                                                                                                       |   |
| - | --------------------------------------------------------------------------------------------------------------------- | - |
|   | CREATE                                                                                                                |   |
|   | <p><strong>Color.ByARGB</strong><br>Construct a color by alpha, red, green, and blue components.</p>                  |   |
|   | <p><strong>Color Range</strong><br>Get a color from a color gradient between a start color and an end color.</p>      |   |
|   | ACTIONS                                                                                                               |   |
|   | <p><strong>Color.Brightness</strong><br>Gets the brightness value for this color.</p>                                 |   |
|   | <p><strong>Color.Components</strong><br>Lists the components for the color in the order: alpha, red, green, blue.</p> |   |
|   | <p><strong>Color.Saturation</strong><br>Gets the saturation value for this color</p>                                  |   |
|   | <p><strong>Color.Hue</strong><br>Gets the hue value for this color.</p>                                               |   |
|   | QUERY                                                                                                                 |   |
|   | <p><strong>Color.Alpha</strong><br>Find the alpha component of a color, 0 to 255.</p>                                 |   |
|   | <p><strong>Color.Blue</strong><br>Find the blue component of a color, 0 to 255.</p>                                   |   |
|   | <p><strong>Color.Green</strong><br>Find the green component of a color, 0 to 255.</p>                                 |   |
|   | <p><strong>Color.Red</strong><br>Find the red component of a color, 0 to 255.</p>                                     |   |

|   |                                                                                           |   |
| - | ----------------------------------------------------------------------------------------- | - |
|   | CREATE                                                                                    |   |
|   | <p><strong>GeometryColor.ByGeometryColor</strong><br>Displays geometry using a color.</p> |   |

### Watch

|   |                                                                               |   |
| - | ----------------------------------------------------------------------------- | - |
|   | ACTIONS                                                                       |   |
|   | <p><strong>View.Watch</strong><br>Visualize the output of node.</p>           |   |
|   | <p><strong>View.Watch 3D</strong><br>Shows a dynamic preview of geometry.</p> |   |

## Input

|   |                                                                                                          |   |
| - | -------------------------------------------------------------------------------------------------------- | - |
|   | ACTIONS                                                                                                  |   |
|   | <p><strong>Boolean</strong><br>Selection between a true and false.</p>                                   |   |
|   | <p><strong>Code Block</strong><br>Allows for DesignScript code to be authored directly.</p>              |   |
|   | <p><strong>Directory Path</strong><br>Allows you to select a directory on the system to get its path</p> |   |
|   | <p><strong>File Path</strong><br>Allows you to select a file on the system to get its filename</p>       |   |
|   | <p><strong>Integer Slider</strong><br>A slider that produces integer values.</p>                         |   |
|   | <p><strong>Number</strong><br>Creates a number.</p>                                                      |   |
|   | <p><strong>Number Slider</strong><br>A slider that produces numeric values.</p>                          |   |
|   | <p><strong>String</strong><br>Creates a string.</p>                                                      |   |
|   | <p><strong>Object.IsNull</strong><br>Determines if the given object is null.</p>                         |   |

## List

|   |                                                                                                                                                                                                                                               |   |
| - | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | - |
|   | CREATE                                                                                                                                                                                                                                        |   |
|   | <p><strong>List.Create</strong><br>Makes a new list out of the given inputs.</p>                                                                                                                                                              |   |
|   | <p><strong>List.Combine</strong><br>Applies a combinator to each element in two sequences</p>                                                                                                                                                 |   |
|   | <p><strong>Number Range</strong><br>Creates a sequence of numbers in the specified range</p>                                                                                                                                                  |   |
|   | <p><strong>Number Sequence</strong><br>Creates a sequence of numbers.</p>                                                                                                                                                                     |   |
|   | ACTIONS                                                                                                                                                                                                                                       |   |
|   | <p><strong>List.Chop</strong><br>Chop a list into a set of lists each containing the given amount of items.</p>                                                                                                                               |   |
|   | <p><strong>List.Count</strong><br>Returns the number of items stored in the given list.</p>                                                                                                                                                   |   |
|   | <p><strong>List.Flatten</strong><br>Flattens a nested list of lists by a certain amount.</p>                                                                                                                                                  |   |
|   | <p><strong>List.FilterByBoolMask</strong><br>Filters a sequence by looking up corresponding indices in a separate list of booleans.</p>                                                                                                       |   |
|   | <p><strong>List.GetItemAtIndex</strong><br>Gets an item from the given list that's located at the specified index.</p>                                                                                                                        |   |
|   | <p><strong>List.Map</strong><br>Applies a function over all elements of a list, generating a new list from the results</p>                                                                                                                    |   |
|   | <p><strong>List.Reverse</strong><br>Creates a new list containing the items of the given list but in reverse order</p>                                                                                                                        |   |
|   | <p><strong>List.ReplaceItemAtIndex</strong><br>Replace an item from the given list that's located at the specified index</p>                                                                                                                  |   |
|   | <p><strong>List.ShiftIndices</strong><br>Shifts indices in the list to the right by the given amount</p>                                                                                                                                      |   |
|   | <p><strong>List.TakeEveryNthItem</strong><br>Fetches items from the given list at indices that are multiples of the given value, after the given offset.</p>                                                                                  |   |
|   | <p><strong>List.Transpose</strong><br>Swaps rows and columns in a list of lists. If there are some rows that are shorter than others, null values are inserted as place holders in the resultant array such that it is always rectangular</p> |   |

## Logic

|   |                                                                                                                                                                                                              |   |
| - | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | - |
|   | ACTIONS                                                                                                                                                                                                      |   |
|   | <p><strong>If</strong><br>Conditional statement. Checks the boolean value of the test input. If the test input is true, the result outputs the true input, otherwise the result outputs the false input.</p> |   |

## Math

|   |                                                                                                                            |   |
| - | -------------------------------------------------------------------------------------------------------------------------- | - |
|   | ACTIONS                                                                                                                    |   |
|   | <p><strong>Math.Cos</strong><br>Fines the cosine of an angle.</p>                                                          |   |
|   | <p><strong>Math.DegreesToRadians</strong><br>Converts an angle in degrees to an angle in radians.</p>                      |   |
|   | <p><strong>Math.Pow</strong><br>Raises a number to the specified power.</p>                                                |   |
|   | <p><strong>Math.RadiansToDegrees</strong><br>Converts an angle in radians to an angle in degrees.</p>                      |   |
|   | <p><strong>Math.RemapRange</strong><br>Adjusts the range of a list of numbers while preserving the distribution ratio.</p> |   |
|   | <p><strong>Math.Sin</strong><br>Finds the sine of an angle.</p>                                                            |   |
|   | <p><strong>Map</strong><br>Maps a value into an input range</p>                                                            |   |

## String

|   |                                                                                                                                                      |   |
| - | ---------------------------------------------------------------------------------------------------------------------------------------------------- | - |
|   | ACTIONS                                                                                                                                              |   |
|   | <p><strong>String.Concat</strong><br>Concatenates multiple strings into a single string.</p>                                                         |   |
|   | <p><strong>String.Contains</strong><br>Determines if the given string contains the given substring.</p>                                              |   |
|   | <p><strong>String.Join</strong><br>Concatenates multiple strings into a single string, inserting the given separator between each joined string.</p> |   |
|   | <p><strong>String.Split</strong><br>Divides a single string into a list of strings, with divisions determined by the given separator strings.</p>    |   |
|   | <p><strong>String.ToNumber</strong><br>Converts a string to an integer or a double.</p>                                                              |   |

## Geometry

### Circle

|   |                                                                                                                                                          |   |
| - | -------------------------------------------------------------------------------------------------------------------------------------------------------- | - |
|   | CREATE                                                                                                                                                   |   |
|   | <p><strong>Circle.ByCenterPointRadius</strong><br>Creates a Circle with input center Point and radius in the world XY plane, with world Z as normal.</p> |   |
|   | <p><strong>Circle.ByPlaneRadius</strong><br>Create a Circle centered at the input Plane origin (root), lying in the input Plane, with given radius.</p>  |   |

|   |                                                                                                                                                                                                    |   |
| - | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | - |
|   | CREATE                                                                                                                                                                                             |   |
|   | <p><strong>CoordinateSystem.ByOrigin</strong><br>Create a CoordinateSystem with origin at input Point, with X and Y Axes set as WCS X and Y axes</p>                                               |   |
|   | <p><strong>CoordinateSystem.ByCylindricalCoordinates</strong><br>Creates a CoordinateSystem at the specified cylindrical coordinate parameters with respect to the specified coordinate system</p> |   |

### Cuboid

|   |                                                                                                                                            |   |
| - | ------------------------------------------------------------------------------------------------------------------------------------------ | - |
|   | CREATE                                                                                                                                     |   |
|   | <p><strong>Cuboid.ByLengths</strong><br>Create a Cuboid centered at WCS origin, with width, length, and height.</p>                        |   |
|   | <p><strong>Cuboid.ByLengths</strong> (origin)</p><p>Create a Cuboid centered at input Point, with specified width, length, and height.</p> |   |
|   | <p><strong>Cuboid.ByLengths</strong> (coordinateSystem)</p><p>Create a Cuboid centered at WCS origin, with width, length, and height.</p>  |   |
|   | <p><strong>Cuboid.ByCorners</strong></p><p>Create a Cuboid spanning from low Point to high Point.</p>                                      |   |
|   | <p><strong>Cuboid.Length</strong></p><p>Return the input dimensions of the Cuboid, NOT the actual world space dimensions. **</p>           |   |
|   | <p><strong>Cuboid.Width</strong></p><p>Return the input dimensions of the Cuboid, NOT the actual world space dimensions. **</p>            |   |
|   | <p><strong>Cuboid.Height</strong></p><p>Return the input dimensions of the Cuboid, NOT the actual world space dimensions. **</p>           |   |
|   | <p><strong>BoundingBox.ToCuboid</strong></p><p>Get the Bounding Box as a solid Cuboid</p>                                                  |   |

{% hint style="warning" %}
\*\*In other words, if you create a Cuboid width (X-axis) length 10, and transform it to a CoordinateSystem with 2 times scaling in X, the width will still be 10. ASM does not allow you to extract the Vertices of a body in any predictable order, so it is impossible to determine the dimensions after a transform.
{% endhint %}

### Curve

|   |                                                                                                                                                  |   |
| - | ------------------------------------------------------------------------------------------------------------------------------------------------ | - |
|   | ACTIONS                                                                                                                                          |   |
|   | <p><strong>Curve.Extrude</strong> (distance)<br>Extrudes a Curve in the normal Vector direction.</p>                                             |   |
|   | <p><strong>Curve.PointAtParameter</strong><br>Get a Point on the Curve at a specified parameter between StartParameter() and EndParameter().</p> |   |

### Geometry Modifiers

|   |                                                                                                                                    |   |
| - | ---------------------------------------------------------------------------------------------------------------------------------- | - |
|   | ACTIONS                                                                                                                            |   |
|   | <p><strong>Geometry.DistanceTo</strong><br>Obtain the distance from this Geometry to another.</p>                                  |   |
|   | <p><strong>Geometry.Explode</strong><br>Separates compound or non-separated elements into their component parts</p>                |   |
|   | <p><strong>Geometry.ImportFromSAT</strong><br>List of imported geometries</p>                                                      |   |
|   | <p><strong>Geometry.Rotate</strong> (basePlane)<br>Rotates an object around the Plane origin and normal by a specified degree.</p> |   |
|   | <p><strong>Geometry.Translate</strong><br>Translates any geometry type by the given distance in the given direction.</p>           |   |

### Line

|   |                                                                                                                                                          |   |
| - | -------------------------------------------------------------------------------------------------------------------------------------------------------- | - |
|   | CREATE                                                                                                                                                   |   |
|   | <p><strong>Line.ByBestFitThroughPoints</strong><br>Creates a Line best approximating a scatter plot of Points.</p>                                       |   |
|   | <p><strong>Line.ByStartPointDirectionLength</strong><br>Create a straight Line starting at Point, extending in Vector direction by specified length.</p> |   |
|   | <p><strong>Line.ByStartPointEndPoint</strong><br>Creates a straight Line between two input Points.</p>                                                   |   |
|   | <p><strong>Line.ByTangency</strong><br>Create a Line tangent to the input Curve, positioned at the parameter Point of the input Curve.</p>               |   |
|   | QUERY                                                                                                                                                    |   |
|   | <p><strong>Line.Direction</strong><br>The direction of the Curve.</p>                                                                                    |   |

### NurbsCurve

|   |                                                                                                               |   |
| - | ------------------------------------------------------------------------------------------------------------- | - |
|   | Create                                                                                                        |   |
|   | <p><strong>NurbsCurve.ByControlPoints</strong><br>Create a BSplineCurve by using explicit control points.</p> |   |
|   | <p><strong>NurbsCurve.ByPoints</strong><br>Create a BSplineCurve by interpolating between points</p>          |   |

### NurbsSurface

|   |                                                                                                                                                                                            |   |
| - | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | - |
|   | Create                                                                                                                                                                                     |   |
|   | <p><strong>NurbsSurface.ByControlPoints</strong><br>Create a NurbsSurface by using explicit control Points with specified U and V degrees.</p>                                             |   |
|   | <p><strong>NurbsSurface.ByPoints</strong><br>Creates a NurbsSurface with specified interpolated points and U and V degrees. The resultant surface will pass through all of the points.</p> |   |

### Plane

|   |                                                                                                                  |   |
| - | ---------------------------------------------------------------------------------------------------------------- | - |
|   | CREATE                                                                                                           |   |
|   | <p><strong>Plane.ByOriginNormal</strong><br>Create a Plane centered at root Point, with input normal Vector.</p> |   |
|   | <p><strong>Plane.XY</strong><br>Creates a plane in the world XY</p>                                              |   |

### Point

|   |                                                                                                                                           |   |
| - | ----------------------------------------------------------------------------------------------------------------------------------------- | - |
|   | CREATE                                                                                                                                    |   |
|   | <p><strong>Point.ByCartesianCoordinates</strong><br>Form a Point in the given coordinate system with 3 cartesian coordinates</p>          |   |
|   | <p><strong>Point.ByCoordinates</strong> (2d)<br>Form a Point in the XY plane given two 2 Cartesian coordinates. The Z component is 0.</p> |   |
|   | <p><strong>Point.ByCoordinates</strong> (3d)<br>Form a Point given 3 Cartesian coordinates.</p>                                           |   |
|   | <p><strong>Point.Origin</strong><br>Get the Origin point (0,0,0)</p>                                                                      |   |
|   | ACTIONS                                                                                                                                   |   |
|   | <p><strong>Point.Add</strong><br>Add a vector to a point. The same as Translate (Vector).</p>                                             |   |
|   | QUERY                                                                                                                                     |   |
|   | <p><strong>Point.X</strong><br>Get the X component of a point</p>                                                                         |   |
|   | <p><strong>Point.Y</strong><br>Get the Y component of a point</p>                                                                         |   |
|   | <p><strong>Point.Z</strong><br>Get the Z component of a point</p>                                                                         |   |

### Polycurve

|   |                                                                                                                                                                                       |   |
| - | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | - |
|   | CREATE                                                                                                                                                                                |   |
|   | <p><strong>Polycurve.ByPoints</strong><br>Make PolyCurve from sequence of lines connecting points. For closed curve last point should be in the same location as the start point.</p> |   |

### Rectangle

|   |                                                                                                                                                                               |   |
| - | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | - |
|   | CREATE                                                                                                                                                                        |   |
|   | <p><strong>Rectangle.ByWidthLength</strong> (Plane)<br>Create a Rectangle centered at input Plane root, with input width (Plane X axis length) and (Plane Y axis length).</p> |   |

### Sphere

|   |                                                                                                                             |   |
| - | --------------------------------------------------------------------------------------------------------------------------- | - |
|   | CREATE                                                                                                                      |   |
|   | <p><strong>Sphere.ByCenterPointRadius</strong><br>Create a Solid Sphere centered at the input Point, with given radius.</p> |   |

### Surface

|   |                                                                                                                                                      |   |
| - | ---------------------------------------------------------------------------------------------------------------------------------------------------- | - |
|   | CREATE                                                                                                                                               |   |
|   | <p><strong>Surface.ByLoft</strong><br>Create a Surface by lofting between input cross section Curves</p>                                             |   |
|   | <p><strong>Surface.ByPatch</strong><br>Create a Surface by filling in the interior of a closed boundary defined by input Curves.</p>                 |   |
|   | ACTIONS                                                                                                                                              |   |
|   | <p><strong>Surface.Offset</strong><br>Offset Surface in direction of Surface normal by specified distance</p>                                        |   |
|   | <p><strong>Surface.PointAtParameter</strong><br>Return the Point at a specified U and V parameters.</p>                                              |   |
|   | <p><strong>Surface.Thicken</strong><br>Thicken Surface into a Solid, extruding in the direction of Surface normals on both sides of the Surface.</p> |   |

### UV

|   |                                                                           |   |
| - | ------------------------------------------------------------------------- | - |
|   | CREATE                                                                    |   |
|   | <p><strong>UV.ByCoordinates</strong><br>Create a UV from two doubles.</p> |   |

### Vector

|   |                                                                                          |   |
| - | ---------------------------------------------------------------------------------------- | - |
|   | CREATE                                                                                   |   |
|   | <p><strong>Vector.ByCoordinates</strong><br>Form a Vector by 3 Euclidean coordinates</p> |   |
|   | <p><strong>Vector.XAxis</strong><br>Gets the canonical X axis Vector (1,0,0)</p>         |   |
|   | <p><strong>Vector.YAxis</strong><br>Gets the canonical Y axis Vector (0,1,0)</p>         |   |
|   | <p><strong>Vector.ZAxis</strong><br>Gets the canonical Z axis Vector (0,0,1)</p>         |   |
|   | ACTIONS                                                                                  |   |
|   | <p><strong>Vector.Normalized</strong><br>Get the normalized version of a vector</p>      |   |

## CoordinateSystem

|   |                                                                                                                                                                                                    |   |
| - | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | - |
|   | CREATE                                                                                                                                                                                             |   |
|   | <p><strong>CoordinateSystem.ByOrigin</strong><br>Create a CoordinateSystem with origin at input Point, with X and Y Axes set as WCS X and Y axes</p>                                               |   |
|   | <p><strong>CoordinateSystem.ByCylindricalCoordinates</strong><br>Creates a CoordinateSystem at the specified cylindrical coordinate parameters with respect to the specified coordinate system</p> |   |

## Operators

|   |                                                                                                                         |   |
| - | ----------------------------------------------------------------------------------------------------------------------- | - |
|   | <p><strong>+</strong><br>Addition</p>                                                                                   |   |
|   | <p><strong>-</strong><br>Subtraction</p>                                                                                |   |
|   | <p><strong>*</strong><br>Multiplication</p>                                                                             |   |
|   | <p><strong>/</strong><br>Division</p>                                                                                   |   |
|   | <p><strong>%</strong><br>Modular Division finds the remainder of the first input after dividing by the second input</p> |   |
|   | <p><strong>&#x3C;</strong><br>Less Than</p>                                                                             |   |
|   | <p><strong>></strong><br>Greater Than</p>                                                                               |   |
|   | <p><strong>==</strong><br>Equality tests for equality between two values.</p>                                           |   |
