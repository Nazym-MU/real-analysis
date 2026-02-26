A sequence converges if and only if it is a Cauchy sequence.

**Proof:**
- $(\Rightarrow)$: [[Theorem 2.6.2]]
- $(\Leftarrow)$: Start with a Cauchy sequence $(x_n)$. Via [[Lemma 2.6.3]], $(x_n)$ is bounded. Hence, we can use the [[Theorem 2.5.5 - Bolzano-Weierstrass|Bolzano Weierstrass Theorem]] to produce a convergent subsequence $(x_{n_k})$. Set $$x =\lim x_{n_k}$$ WTS: $(x_n) \to x$.
Let $\epsilon > 0$. Because $(x_n)$ is Cauchy, $\exists \ N \in \mathbb N$ s.t. $$|x_n-x_m| < \frac{\epsilon}{2}$$ whenever $m, n \geq N$. Since $x_{n_k} \to x$, choose a term $x_{n_K}$ in this subsequence with $n_K \geq N$ and $$|x_{n_K}-x| < \frac{\epsilon}{2}$$
If $n \geq N$, then use the [[Triangle inequality]] to show that $$|x_n-x| \leq |x_n-x_{n_K}| + |x_{n_K} - x| < \frac{\epsilon}{2} + \frac{\epsilon}{2} = \epsilon. \qquad \square$$
