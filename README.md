# FLEXIL GRID

Flexil a contracted version of the Latin word _flexile_, meaning - _pliant, pliable, supple_.

Flexil grid is an adaptable, flexible, gracefully adjusting flexbox based hybrid grid.  Flexil's gutters are a fixed 1.5em, contributing to the vertical rhythm.

## GRID SYSTEM

Flexil's grid system is inspired by many of the great grid systems, providing some familiarity.

Currently, there are 3 grid sizes: small, medium, and large.

### Small
Flexil's small (_a.k.a. mobile_) grid is a **maximum** of four columns.  The small grid is fractional and can be divided in either **halves, thirds, fourths, or full-width**.

The following are the classes for the **small** grid:
+ `.full`, `.sm-4-4`, `.sm-3-3`
+ `.three-fourths`, `.sm-3-4`
+ `.two-thirds`, `.sm-2-3`
+ `.one-half`, `.sm-2-4`
+ `.one-third`, `.sm-1-3`
+ `.one-fourth`, `.sm-1-4`

### Medium
Flexil's medium (_a.k.a. tablet_) grid is 6 columns.  Flexil's small grid fractional divisions can be used in medium view.

The following are the classes for the **medium** grid:
+ `.full`, `.md-6-6`
+ `.md-5-6`
+ _`.three-fourths*`_
+ `.md-4-6`, `.two-thirds`
+ `.one-half`, `.md-3-6`
+ `.md-2-6`, `.one-third`
+ _`.one-fourth*`_
+ `.md-1-6`

\* _NOTE: While fourth divisions can be used within the medium grid, there may be unexpected side-effects when mixed with the medium grid's sixth divisions.  It is recommended, when using fourth divisions within the medium grid, to keep them separate from the sixth divisions._
