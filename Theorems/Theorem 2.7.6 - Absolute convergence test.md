If the series $\sum^\infty_{n=1}|a_n|$ converges, then  $\sum^\infty_{n=1}a_n$ converges as well.

**Proof:**
Because $\sum^\infty_{n=1}|a_n|$ converges, we know that given $\epsilon > 0, \ \exists N \in \mathbb N$ s.t. $$|a_{m+1}| + |a_{m+2}| + \cdots + |a_n| < \epsilon$$
for all $n > m \geq N$. By the triangle inequality, $$|a_{m+1} + a_{m+2} + \cdots + a_n| \leq |a_{m+1}| + |a_{m+2}| + \cdots + |a_n|,$$ so the sufficiency of the [[Theorem 2.6.4 - Cauchy Criterion]] guarantees that $\sum_{n=1}^\infty a_n$ also converges. $\qquad \square$