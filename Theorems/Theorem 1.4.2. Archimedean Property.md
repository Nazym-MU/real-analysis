1. Given any $x \in R$, there exists $n \in N$ s.t. $n > x$
2. Given any real number $y > 0$, there exists $n \in \mathbb N$ s.t. $1/n < y$

**Proof:**
1. This means that $N$ is not bounded above. By contradiction, assume $N$ is bounded above. By AoC, it should have a least upper bound. Let $\alpha = \sup N$. Then, $\alpha -1$ is no longer an upper bound, via [[Lemma 1.3.8]]. Therefore, there exists $n \in N$ s.t. $\alpha - 1 < n$. This is equivalent to $\alpha < n + 1$. Because $n + 1 \in N$, we have a contradiction to the fact that $\alpha$ is supposed to be the upper bound for $N$. 
2. Follows from part (1) by letting $x = 1/y$. $\square$
