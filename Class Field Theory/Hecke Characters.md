Let $k$ denote a number field and $\mathcal{O}$ its ring of integers.

For any fraction ideal $\mathfrak{a}$, $$\mathfrak{a} = \prod_\mathfrak{p}\mathfrak{p}^{e_{\mathfrak{p}}} \text{, each } e_\mathfrak{p} \in \mathbb{Z}, e_\mathfrak{p} = 0 \text{ for almost all } \mathfrak{p}$$
we say that the maximal ideal $\mathfrak{p}$ **appears in** $\mathfrak{a}$ if $e_\mathfrak{p} \neq 0$. If $\mathfrak{b}$ is a second fractional ideal then we say that $\mathfrak{a}$ and $\mathfrak{b}$ are coprime if no $\mathfrak{p}$ appears in both $\mathfrak{a}$ and $\mathfrak{b}$. 

Let $\mathfrak{f}$ be a nontrivial ideal of $\mathcal{O}$; that is, $\mathfrak{f}$ is neither $(0)$ nor $\mathcal{O}$. The elements of $k^{\times}$ that generate fraction ideals coprime to $\mathfrak{f}$ form a subgroup. $$k(\mathfrak{f}) = \{\alpha \in k^{\times}:((\alpha), \mathfrak{f}) = 1\}$$
Consider the following set $$k(\mathfrak{f})\mathfrak{f} = \{
		\delta \in k : v_\mathfrak{p}((\delta)) \geq v_\mathfrak{p}(\mathfrak{f}) \text{ for all } \mathfrak{p} \text{ that appear in } \mathfrak{f}
\}$$
1. $0 \in k(\mathfrak{f})\mathfrak{f}$ as $0 \in \mathfrak{f}$
2. $k(\mathfrak{f})\mathfrak{f}$ is closed under multiplication by $k(\mathfrak{f})$; in particular, it is closed under negation.
3. $k(\mathfrak{f})\mathfrak{f}$ is closed under addition

**Definition (Multiplication Congruence):** For any pair of nonzero field elements $\alpha, \beta \in k(\mathfrak{f})$, the condition $$
\alpha = \beta \text{ mod}^{\times} \space \mathfrak{f}
$$means 
$$
\beta - \alpha \in k(\mathfrak{f})\mathfrak{f}
$$
As $k(\mathfrak{f})\mathfrak{f}$ is closed under multiplication by $k(\mathfrak{f})$, if we have $\alpha, \beta, \gamma, \delta \in k(\mathfrak{f})$, $$
\text{if } \alpha = \beta \text{ mod}^{\times} \space \mathfrak{f} \text{ and } \gamma = \delta \text{ mod}^{\times} \space \mathfrak{f} \text{ then } \alpha\gamma = \beta\delta \text{ mod}^{\times} \space \mathfrak{f}
$$
Now consider the subgroup $k_\mathfrak{f}$ of $k(\mathfrak{f})$ that will give the desired quotient group $k(\mathfrak{f})/k_\mathfrak{f}$,$$k_\mathfrak{f} = 1 + k(\mathfrak{f})\mathfrak{f} = \{ \alpha \in k^{\times} : \alpha = 1 \text{ mod}^{\times} \space \mathfrak{f}\} \subset k(\mathfrak{f})$$