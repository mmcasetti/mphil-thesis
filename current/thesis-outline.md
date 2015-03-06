# Complexity of the Gale String Problem for Equilibrium Computation in Games

## Abstract

(See other file)

## Introduction

What, why and overview of tools used

Intro to idea of PPAD goes in here

## Games, Polytopes and Gale Strings
[definitions & background]

### Games and Nash equilibria

Notation for games, Nash Equilibria

### Best Response Polytopes

Best response polytopes

Polytopes to games (NE can be found via polytopes, polytopes can be used to create games) (vS 1999 - nxn games w/ more than 2^n equilibria)

### Cyclic Polytopes and Gale strings
new outline:
* def CP
* def GS
* example GS, d even
* exmple GS, d odd
* thm Gale (true for d even and odd!)
* graphics to go w/ thm
* prop even d (use modulo, then find a nice notation & drop it)
* assume that from now on d even (unless o/w spec - if parity thm for odd d too)

Special case: cyclic polytopes.

Cyclic polytopes can be represented w/ a combinatorial structure - Gale strings.

### Labeling and ANOTHER GALE

Labeling, which gives the reason for studying ANOTHER GALE

## Algorithms and Complexity Results
[main results: thms]

### Pivoting

Path on Gale Strings // Cyclic polytopes - without labels

### The Lemke-Howson Algorithm and Parity
new outline:
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

PPAD? it goes off topic...

### The complexity of GALE and ANOTHER GALE
outline:
* GALE introduced as accessory problem
* PM def
* main thm for GALE
* ex of construction: if there is / there isn't PM
* main theorem for ANOTHER GALE
* ex: double edge / all edges in PM are single / all single edges

## Further results

The framework provided by our result led to further questions, related to the
issue of the *sign* of an index (Merschen, VvS)

[Graphics of endpoints of LHG on all CLGS for G(d,n)]

Open problems (?)

## Appendix: result on PPAD-completeness proof

## Appendix: Notation
[Maybe]

## Biblio
