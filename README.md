# Art-Gallery-Solver
The Art Gallery Problem is formulated in geometry as the minimum number of guards that need to be placed in an n-vertex simple polygon such that all points of the interior are visible. A simple polygon is a connected closed region whose boundary is defined by a finite number of line segments.  It is a family of related visibility problems in computational geometry. Visibility is defined such that two points u and v are mutually visible if the line segment joining them lies inside the polygon. Here, we discuss several variants. The common terms used in the variants discussed below:

A simple (not necessarily convex) polygon P to describe the art gallery.
A set of points S to describe the guards where each guard is represented by a point in P.
A rule that a point A ∈ S can guard another point B ∈ P if and only if A ∈ S, B ∈ P and line segment AB is contained in P.
A question on whether all points in polygon P are guarded by S.
Many variants of this Art Gallery Problem are classified as NP-hard problems. Here, we will focus on the ones that admit polynomial solutions:

Variant 1: Determine the upper bound of the smallest size of set S.
Variant 2: Determine if ∃ a critical point C in polygon P and ∃ another point D ∈ P such that if the guard is at position C, the guard cannot protect point D.
Variant 3: Determine if polygon P can be guarded with just one guard.
Variant 4: Determine the smallest size of set S if the guards can only be placed at the vertices of polygon P and only the vertices need to be guarded.
Note that there are many more variants and at least one book has been written for it.
