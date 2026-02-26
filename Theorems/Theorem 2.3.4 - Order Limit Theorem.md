Assume $\lim a_n = a$ and $\lim b_n = b$. 
1. If $a_n \geq 0 \ \forall \ n\in \mathbb N$, then $a\geq 0$.
	1. In other words, convergent sequences that are eventually nonnegative converge to nonnegative limits.
2. If $a_n \leq b_n \ \forall \ n\in \mathbb N$, then $a \leq b$.
3. If $\exists \ c\in \mathbb R$ for which $c\leq b_n \ \forall \ n\in \mathbb N$, then $c \leq b$. Similarly, if $a_n \leq c \ \forall \ n \in \mathbb N$, then $a \leq c$.

**Proof:**
1. Proof by contradiction: assume $a < 0$. Goal: produce a term in the sequence that is also less than zero. Consider $\epsilon = |a|$. By definition of convergence, we can find an $N$ s.t. $|a_n-a|<|a| \ \forall \ n \geq N$. This means $|a_N - a| < |a|$, which implies $a_N < 0$. This contradicts the hypothesis that $a_N \geq 0  $\ \therefore$   $a \geq 0$. 
2. By [[Theorem 2.3.3 - Algebraic Limit Theorem|Algebraic Limit Theorem]], the sequence $(b_n - a_n)$ converges to $b-a$. Because $b_n - a_n \geq 0$, apply part 1 to get that $b - a \geq 0$.
3. Take $a_n = c \ \forall n \in \mathbb N$, and apply part 2. 