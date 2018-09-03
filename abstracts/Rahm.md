---
layout: default
permalink: /abstracts/subdivision
---

## Alexander D. Rahm

### The Rigid Facets Subdivision Algorithm in GAP

Understanding the structure of the cohomology of arithmetic groups is
a very important problem with relations to number theory and various
K-theoretic areas. Explicit cohomology computations usually proceed
via the study of the actions of the arithmetic groups on their
associated symmetric spaces, and recent years have seen several
advances in algorithmic computation of equivariant cell structures for
these actions. To approach computations of Farrell-Tate and Bredon
(co)homology of arithmetic groups, one needs cell complexes having a
rigidity property: cell stabilizers must fix their cells
pointwise. The previously known algorithms (using Voronoi
decompositions and such techniques do not provide complexes with this
rigidity property, and this leads to a significant bottleneck, both
for the computation of Farrell-Tate cohomology (resp. the torsion at
small prime numbers in group cohomology) of arithmetic groups as well
as for the computation of Bredon homology. In theory, it is always
possible to obtain this rigidity property via the barycentric
subdivision. However, the barycentric subdivision of an n-dimensional
cell complex can multiply the number of cells by (n+1)! and thus
easily let the memory stack overflow. We present an algorithm
implemented in GAP, called rigid facets subdivision, which subdivides
cell complexes for arithmetic groups such that stabilisers fix their
cells pointwise, but only leads to a controlled increase (in terms of
sizes of stabilizer groups) in the number of cells, avoiding an
explosion of the data volume. The GAP implementation of the algorithm
shows that cases like PSL_4(Z) can effectively be treated with it,
using commonly available machine resources.
