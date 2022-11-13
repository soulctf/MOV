## Ring Norm

Given an integral domain $R$, we can define a function $N : R \rightarrow \mathbb{Z}^{+} \cup \{0\}$ with $N(0) = 0$ called a norm. If $N(r) > 0$, for all $r \neq 0$, we call N a positive norm.

Note there can be multiple norms for a given integral domain R.

## Euclidean Domain Definition

An integral domain $R$ is called an euclidean domain if there is a norm $N$ such that for any two element $a, b \in R$ with $b \neq 0$, then there exists elements $q,r \in R$ such with $$a = qb + r \text{ with r = 0 or } N(r) < N(b)$$
$q$ here is called the quotient and $r$ the remainder of the division.

This allows us to generalize the idea of the euclidean algorithm to some integral domains.

## All Euclidean Domains are [[Principle Ideal Domains|Principle Domains]]  (Proof)

Let $I$ be an ideal of the euclidean domain $R$. If $I = (0)$ we are done. Else we can take $d$ to be any nonzero element in $I$ such that $N(d)$ is minimal (norm is a map to the nonnegative integers so there is a minimum).

$(d) \subseteq I$ as $d \in I$, so we just need to show the reverse inclusion.

Let $a$ be an element of $I$. Since $R$ is an euclidean algorithm, we can write $a = qd + r$ with $N(r) < N(d)$. Then $r = a - qd$, and $r \in I$, so by construction of $d$, $N(r)$ must be $0$. Thus $a \in (d)$, and as $a$ was arbitrary, $I \in (d)$. 

We now get $I = (d)$.