Ever convergent sequence is bounded.

**Proof:**
Assume ($x_n$) converges to a limit $l$. This means that given a particular value of $\epsilon$, we know that there must exist an $N \in \mathbb N$ such that if $n \geq N$, then $x_n$ is in the interval ($l-\epsilon, l+\epsilon$). We can certainly conclude that $$|x_n| < |l|+\epsilon$$ for all $n \geq N$.
Because there are only a finite number of terms that come before the $N$th term (outside the interval), we let $$M = \max \{|x_1|, |x_2|, |x_3|, ..., |x_{N-1}|, |l|+\epsilon\}$$
It follows that $|x_n| \leq M$ for all $n \in \mathbb N$. $\qquad \qquad \qquad \qquad \qquad \qquad \qquad \qquad \qquad \qquad \qquad \square$

$M$ certainly being greater than all elements $x_n$ is probably because of the Archimedian property, which states that there exists $n \in \mathbb N$ s.t. $n > x_n$.
