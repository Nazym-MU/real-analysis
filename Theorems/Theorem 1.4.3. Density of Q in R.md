For every two numbers $a$ and $b$ with $a < b$, there exists a rational number $r$ satisfying $a < r < b$. 
$$\forall a, b \in R \text{ with } a < b, \exists r \in Q \text{ s.t. } a < r < b$$
**Proof:**
By definition of a rational number, $m \in Z, n \in Z \text{ s.t. } a < m/n < b$, which we can rewrite as $na < m < nb$.
Via [[Theorem 1.4.2. Archimedean Property]], we may pick $n \in N$ large enough so that $1/n < b - a$.
Choose $m \in Z$ s.t. $m - 1 \leq na < m$
From there, we know that $a < m/n$ and $a < b - 1/n$ (from the earlier inequality).

This allows us to rewrite $m - 1 \leq na$ as:
$$m \leq na + 1 < n(b - 1/n) + 1 = nb$$
Because $m < nb$ implies $m/n < b$, we have $a < m/n < b$. $\square$

This means that $Q$ is dense in $R$. Irrational numbers are dense in $R$ as well.