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
	1. $\phi(x+y) = \phi(x) + \phi(y)$, for all $x, y \in M$ and 
	2. $\phi(rx) = r\phi(x)$, for all $x \in M, r\in R$
2. We call an $R$-module homomorphism an isomorphism if it is injective and surjective. Modules are called isomorphic if there exists a $R$-module isomorphism between them.
3. The kernel of $\phi$ is defined as $\ker\phi = \{ m \in M \mid \phi(m) = 0\}$ and the image of $\phi$ is defined as $\phi(M) = \{n \in N \mid n = \phi(m) \text{ for some } m \in M \}$    
4. Define $\mathrm{Hom}_{R}(M,N)$ to be the set of all module homomorphisms from $M$ to $N$. This is an abelian group as we define $$(\phi + \psi)(m) = \phi(m) + \psi(m)$$
