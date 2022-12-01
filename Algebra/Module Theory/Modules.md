## Module Definition

Let $R$ be a [[Rings|ring]]. An $R$-module is a set $M$ together with:
1. A binary operation $+$ on $M$ such that $M$ is an abelian [[Groups|group]]
2. An action of $R$ on $M$ denoted by $rm$ which satisfies
	1. $(r +s)m = rm + sm$, for all $r, s \in R$, $m \in M$
	2. (rs)m = r(sm), for all $r, s \in R$, $m \in M$
	3. $r(m + n) = rm + rn$, for all $r, s \in R$, $m \in M$

If the ring is unital, we add that $1m = m$, for all $m \in M$

We denote $M$ as a left or right module if the action of $R$ on $M$ is a left or right action only respectively.

A submodule $N$ of $M$ is a subgroup of $M$ such that for all $r \in R$, and $n \in N$ $rn \in N$.

Modules over a field $F$ and vector spaces over $F$ are the same, and submodules are subspaces. Every $R$-module $M$ has two submodules $M$ and $0$.



## Quotient Modules and Module Homomorphisms

Let $R$ be a [[Rings|ring]] and let $M$ and $N$ be $R$-modules
	1. A map $\phi: M \rightarrow N$ is an **$R$-module homomorphism** if it respects the $R$-module structures of $M$ and $N$, i.e.
	2. 