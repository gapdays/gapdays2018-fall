---
layout: default
permalink: /abstracts/OSCAR
---

## Sebastian Gutsche

### GAP-Julia integration

OSCAR (Open Source Computer Algebra Resource) is a new project to
build a visionary computer algebra system integrating GAP, Singular,
polymake, and Antic by using the Julia programming language.

The GAP package JuliaInterface and the Julia package Gap.jl provide
the low-level part of integrating GAP and Julia. They combine several
features, including
* accessing all functionality in Julia from GAP,
* accessing all functionality in GAP from Julia,
* and conversion of basic types between GAP and Julia.

Unlike interfaces, the integration aims providing compatibility at the
lowest level, trying to make the wall separating the two systems as
low as possible. To achieve this, several technical difficulties had
to be tackled, of which some will be presented in the talk.

Together with the integration of Singular and polymake into Julia
(also part of the OSCAR project), JuliaInterface and Gap.jl will be
used to provide integration of GAP with Singular and polymake.

Because of the low penalty when switching between the GAP and the
Julia layer, this integration enables one to write algorithms
combining the computational power of all four systems.

In this regard, JuliaInterface can be used to replace incomplete
interface from GAP to polymake and the outdated interface from GAP to
Singular, using as few binding code as possible to transparently
access all foreign functionality.

Furthermore, the highly efficient integration of Julia into GAP allows
one to implement fast versions of algorithms for GAP in Julia instead
of C.

This is joint work with Reimer Behrends, Thomas Breuer, William Hart,
Max Horn, and Markus Pfeiffer.
