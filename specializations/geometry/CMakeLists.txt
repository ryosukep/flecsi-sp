#~----------------------------------------------------------------------------~#
# Copyright (c) 2016 Los Alamos National Laboratory, LLC
# All rights reserved
#~----------------------------------------------------------------------------~#

set(geometry_HEADERS
  point.h
  space_vector.h
  shapes/geometric_shapes.h
  shapes/hexahedron.h
  shapes/polygon.h
  shapes/polyhedron.h
  shapes/quadrilateral.h
  shapes/tetrahedron.h
  shapes/triangle.h

  PARENT_SCOPE
)

set(geometry_SOURCES
  PARENT_SCOPE
)

cinch_add_unit(point
  SOURCES test/point.cc
)

cinch_add_unit(space_vector
  SOURCES test/space_vector.cc
)

#~---------------------------------------------------------------------------~-#
# Formatting options
# vim: set tabstop=2 shiftwidth=2 expandtab :
#~---------------------------------------------------------------------------~-#
