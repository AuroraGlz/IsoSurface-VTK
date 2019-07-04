# IsoSurface-VTK
VTK format for mayavi2 or  ParaView

From VTK format created isosurface script, running background through bash in linux

Read input.iso, get out.png

input.iso =Structure=

# vtk DataFile Version 2.0 
Density field
ASCII
DATASET STRUCTURED_GRID
DIMENSIONS    nx    ny    nz
POINTS  nx*ny*nz float
 .
 .
 .
 x y z off all celds
 .
 .
 .
 [withe space]
POINT_DATA nx*ny*nz
SCALARS scalars float
LOOKUP_TABLE default
.
.
.
one scalar field
.
.
.
 [withe space]
VECTORS vectors float
.
.
.
x y z vector field
.
.
.
=============================END .vtk==========================
run in a terminal with bash
