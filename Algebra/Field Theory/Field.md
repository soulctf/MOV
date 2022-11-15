A **Field** is a set $F$ with binary operations $+$ and $\ast$ such that 
1. $(F, +)$ is a commutative group
2. $(F^{\times}, \ast)$, where $F^\times$ = $F \space \backslash \{0\}$ 
3.  The distributive laws hold
Thus a field is a commutative ring such that every nonzero element has an inverse. 

A **subfield** $S$ of $F$ is a subring of $F$ that is also a field. It inherits its field structure from $F$

**Lemma 1:** A nonzero commutative ring $R$ is a field if and only if it has no ideals others than $(0)$ and $(R)$.

A **homomorphism of fields** is simply a homomorphism of rings. It is always injective as its kernel is a proper ideal (it doesn't contain 1), which must therefore be zero.

An **$F$-algebra** (or an algebra over $F$), is a ring $R$ containing $F$ as a subring. A **homomorphism of $F$-algebras** $\alpha : R \rightarrow R'$ is a homomorphism of rings such that $\alpha(c) = c$ for every $c \in F$. An $F$