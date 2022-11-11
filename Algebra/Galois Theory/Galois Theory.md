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

## Extensions

An **extension** of a field $F$ is a field containing $F$ as a subfield. This extension can be though of an $F$-algebra whose underlying ring is a field. An extension $E$ of $F$ is an $F$-vector space whose dimension is called the degree $$ 