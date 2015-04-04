# Complexity of the Gale String Problem for Equilibrium Computation in Games

## Abstract

(max 300 words)

## Introduction

* why what how - the usual
* PPAD (it won't come back until appendix but it's in the background)

## Complexity, Games, Labels, Polytopes, Strings

### Some complexity classes

Computational complexity background!

### Normal Form Games and Nash Equilibria

* basic definitions: game, NE

### Some Geometrical Notation

* polytopes

### Bimatrix Games, Labels and Polytopes

* Idea: Polytopes to games (NE can be found via polytopes, polytopes can be
used to create games) (vS 1999 - nxn games w/ more than 2^n equilibria)
* see all articles vS & past theses


### Cyclic Polytopes and Gale Strings

* def CP
* def GS
* example GS, d even
* exmple GS, d odd
* thm Gale (true for d even and odd!)
* graphics to go w/ thm
* prop even d (use modulo, then find a nice notation & drop it)
* assume that from now on d even (unless o/w spec - if parity thm for odd d
too)
* labeling on GS
* corresp to polytope
* case odd, even just as ex (?)
* ANOTHER GALE

## Algorithms and Complexity Results

### Pivoting and the LH algorithm

[Path on Gale Strings // Cyclic polytopes - without labels]

* almost completely labeled GS
* LH for Gale
* even no of CLGS
- holds for d odd too (?)
- not for GS in general
* examples (by pf thm that GS + label => unique, ex show that converse not true)

Lemke-Howson for Gale // on Poly - we add labels

[A lot of tabulars and graphics! to show running pivoting and LHG between two
(A)CLGS]

[Theorem: if there's a GS, there's another one
* will be used in next section
* will be used to talk about sign in further results
and PPAD in appendix]

#### Exponentially Long Paths

PPAD: DGP & CD + SvS results = why ANOTHER GALE in P is important!

### The complexity of GALE and ANOTHER GALE

* GALE introduced as accessory problem
* PM def
* main thm for GALE
* ex of construction: if there is / there isn't PM
* main theorem for ANOTHER GALE
* ex: double edge / all edges in PM are single / all single edges

## Further results

[Euler graphs --> oiks. Graph of proof: Euler graph, 1-oik, so
PM=room partition.]

[Exchange algorithm in general; alt proof of parity of GS; contrast
w/ Morris that shows exp cases for LHG.]

[PPAD comes back - "D" in sign]

[note that w/ oiks not always oriented - example RPs of octahedron]

[Brightwell on finding number of matchings (in Euler?) #P-complete.]

[*sign* of an index (Merschen, VvS)]

[Open problems (?)]

## Appendix: a Result on the PPAD-completeness of NASH

* see MSc thesis

## Appendix: Notation

[Maybe]

## Biblio
