Suppose $(b_n)$ is decreasing and satisfies $b_n \ge 0$ for all $n \in \mathbb{N}$. Then the series $\sum_{n=1}^{\infty} b_n$ converges if and only if the series
$$\sum_{n=0}^{\infty} 2^n b_{2^n} = b_1 + 2b_2 + 4b_4 + 8b_8 + 16b_{16} + \cdots$$converges.

---
**Proof.** First, assume that $\sum_{n=0}^{\infty} 2^n b_{2^n}$ converges. [[Theorem 2.3.2]] guarantees that the partial sums
$$t_k = b_1 + 2b_2 + 4b_4 + \cdots + 2^k b_{2^k}$$
are bounded; that is, there exists an $M > 0$ such that $t_k \le M$ for all $k \in \mathbb{N}$. We want to prove that $\sum_{n=1}^{\infty} b_n$ converges. Because $b_n \ge 0$, we know that the partial sums are increasing, so we only need to show that $s_m = b_1 + b_2 + b_3 + \cdots + b_m$ is bounded.

Fix $m$ and let $k$ be large enough to ensure $m \le 2^{k+1} - 1$. Then $s_m \le s_{2^{k+1}-1}$ and
$$s_{2^{k+1}-1} = b_1 + (b_2 + b_3) + (b_4 + b_5 + b_6 + b_7) + \cdots + (b_{2^k} + \cdots + b_{2^{k+1}-1})$$
$$\le b_1 + (b_2 + b_2) + (b_4 + b_4 + b_4 + b_4) + \cdots + (b_{2^k} + \cdots + b_{2^k})$$
$$= b_1 + 2b_2 + 4b_4 + \cdots + 2^k b_{2^k} = t_k$$

Thus, $s_m \le t_k \le M$ and the sequence $(s_m)$ is bounded. By the [[Theorem 2.4.2 - Monotone Convergence Theorem]], we can conclude that $\sum_{n=1}^{\infty} b_n$  converges.

The proof that $\sum_{n=0}^{\infty} 2^n b_{2^n}$ diverges implies $\sum_{n=1}^{\infty} b_n$ diverges is similar to [[Example 2.4.5 - Harmonic series]].