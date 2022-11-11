## Factoring Polynomials

**Proposition 1:** Let $r \in \mathbb{Q}$ be a root of the polynomial $a_{m}X^{m} + a_{m-1}X^{m-1} ... + a_{1}X + a_0$ , and write $r = c/d$, then $c \mid a_0$ and $d \mid a_m$ 

Proof: Plugging in r to the polynomial and then multiplying by $d^m$ we get the following $$a_{m}c^{m}+ a_{m-1}c^{m-1}d+ ... + a_{0}d^{m}=0$$ which implies that $d \mid a_{m}c^{m}$ and $c \mid a_{0}$

**Proposition 2 (Gauss's Lemma):** Let $f(X) \in Z[X]$. If $f(X)$ factors nontrivally in $\mathbb[X]$, then it factors nontrivally in $\mathbb{Z}[X]$

**Proposition 3:** If $f \in \mathbb{Z}[X]$  is monic, then every monic factor of $f$ in $Q[X]$ lies in $Z[X]$.

**Proposition 4 (Eisenstein's Criterion):** Let $f = a_{m}X^{m} + a_{m-1}X^{m-1} ... + a_{1}X + a_0$, $a_{i} \in \mathbb{Z}[X]$. Suppose that there is a prime number $p$ such that:
1.  $p$ does not divide $a_m$
2.  $p$ divides $a_{m-1}, ... , a_0$ 
3. $p^{2}$ does not divide $a_0$
Then $f$ is irreducible in $\mathbb{Q}[X]$.

## Extensions Basics

An **extension** of a field $F$ is a field containing $F$ as a subfield. This extension can be though of an $F$-algebra whose underlying ring is a field. An extension $E$ of $F$ is an $F$-vector space whose dimension is called the **degree** $|E:F|$  of $E$ over $F$. An extension is said to be **finite** (resp. **quadratic, cubic**, etc.) if its degree is finite.

When $E$ and $E'$ are extensions of $F$, an $F$-**homomorphism** $E \rightarrow E'$ is a homorphism $\phi : E \rightarrow E'$ such that $\phi(c) = c$ for all $c \in F$. An $F$-**isomorphism** is a bijective $F$-homomorphism

**Proposition 1 (Multiplicity of Degrees):** Consider extensions $L \supset E\supset F$.  Then $L / F$ is of finite degree iff $L/E$ and $E/F$ are both of finite degree, in which case $$|L:F| = |L:E| \space |E:F|$$ 
Proof: If $L$ is finite over $F$, then is is finite over $E$, and as $E$ is a subspace of a finite dimensional $F$-vector space, it is also finite-dimensional.

Thus now assume that $L / E$ and $E / F$ are of finite degree, and let $(e_i)_{1 \leq i \leq m}$ be a basis for $E$ as an $F$-vector space and let $(l_i)_{1 \leq j \leq n}$ be a basis for $L$ as an $E$-vector space. We will now show that $(e_il_j)_{1 \leq i \leq m, 1 \leq j \leq n}$ is a basis for $L$ over $F$.

First, $(e_il_j)_{1 \leq i \leq m, 1 \leq j \leq n}$ space L. Let $\gamma \in L$. Then, because $(l_i)_{1 \leq j \leq n}$ space $L$ as an $E$-vector space, $$\gamma = \sum\limits_{j}\alpha_jl_{j} \space \text{ for some } \alpha_{j} \in F$$
and because $(e_i)_{1 \leq i \leq m}$ spans $E$ as an $F$-vector space, $$\alpha_{j}= \sum\limits_{i}a_{ij}e_{j} \space \text{some } a_{ij} \in F.$$
Putting these together we find that $$\gamma = \sum\limits_{i,j}a_{ij}e_{i}l_{j}$$
Second, this basis is linearly independent as the sum of the $e_i$ terms can only be 0 if they are all 0, and then same for the $l_j$ terms.

## Extension contd.

An extension