Grid (Inverse distance to a power)
==================================

Description
-----------

<put algortithm description here>

Parameters
----------

``Input layer`` [vector: point]
  <put parameter description here>

``Z field`` [tablefield: numeric]
  Optional.

  <put parameter description here>

``Power`` [number]
  <put parameter description here>

  Default: *2.0*

``Smothing`` [number]
  <put parameter description here>

  Default: *0.0*

``Radius 1`` [number]
  <put parameter description here>

  Default: *0.0*

``Radius 2`` [number]
  <put parameter description here>

  Default: *0.0*

``Max points`` [number]
  <put parameter description here>

  Default: *0.0*

``Min points`` [number]
  <put parameter description here>

  Default: *0.0*

``Angle`` [number]
  <put parameter description here>

  Default: *0.0*

``Nodata`` [number]
  <put parameter description here>

  Default: *0.0*

``Output raster type`` [selection]
  <put parameter description here>

  Options:

  * 0 --- Byte
  * 1 --- Int16
  * 2 --- UInt16
  * 3 --- UInt32
  * 4 --- Int32
  * 5 --- Float32
  * 6 --- Float64
  * 7 --- CInt16
  * 8 --- CInt32
  * 9 --- CFloat32
  * 10 --- CFloat64

  Default: *5*

Outputs
-------

``Output file`` [raster]
  <put output description here>

Console usage
-------------

::

  processing.runalg('gdalogr:gridinvdist', input, z_field, power, smothing, radius_1, radius_2, max_points, min_points, angle, nodata, rtype, output)

See also
--------

