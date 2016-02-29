# Complexity of the Gale String Problem for Equilibrium Computation in Games

MPhil thesis by Marta Maria Casetti

Department of Mathematics - London School of Economics and Political Science

January 2016


## Abstract

This thesis presents a report on original research, extending a result
published as joint work with Merschen and von Stengel in *Electronic Notes in Discrete Mathematics* [2010]. We present a polynomial time algorithm for two problems on labeled Gale strings, a combinatorial structure introduced by Gale [1963] that can be used in the representation of a particular class of games.

These games were used by Savani and von Stengel [2006] as an example of exponential running time for the classical Lemke-Howson algorithm [1964] to find a Nash equilibrium of a bimatrix game. It was therefore conjectured that solving} these games was a complete problem in the class **PPAD** (Polynomial Parity Argument, Directed version, see Papadimitriou [1994]). In turn, a major motivation for the definition of PPAD was the study of complementary pivoting methods, such as the Lemke-Howson algorithm.

Our result, unexpectedly, sets apart this class of games as a case
where a Nash equilibrium can be found in polynomial time. Since Daskalakis, Goldberg and Papaditrimiou [2009] and Chen and Deng [2006] proved that finding a Nash equilibrium in general normal-form games is **PPAD**-complete, we have a special class of games, unless **PPAD** = **P**.

Our proof exploits two results. As seen in Savani and von Stengel [2006, 2015], we represent the Nash equilibria of these special games as Gale strings.We then give a graph where the perfect matchings correspond to Nash equilibria via Gale strings, and we exploit Edmonds' polynomial-time algorithm for a perfect matching in a graph [1965]. The proof given in Casetti, Merschen and von Stengel [2010] covered only the case of even-dimensional Gale strings; here we extend the result to the general case.

Merschen [2012] and Végh and von Stengel [2015] expanded on our ideas, proving further results on the index of Nash equilibria (see Shapley [1973]) in the framework of *oiks* introduced by Edmonds [2009] and Edmonds and Sanità [2010].

## Copyright Notice

I certify that this thesis I have presented for examination for the MPhil degree of the London School of Economics and Political Science is based on joint work with Julian Merschen and Bernhard von Stengel, published in *Electronic Notes in Discrete Mathematics* [2010].

The improvement given by Proposition 2.4, and the consequent extensions of Theorem 11 and Theorem 12 to the case of *d* odd, are an original result.

The copyright of this thesis rests with the author. Quotation is permitted, provided that full acknowledgement is made. This thesis may not be reproduced without my prior written consent.

I warrant that this authorisation does not, to the best of my belief, infringe the rights of any third party.
