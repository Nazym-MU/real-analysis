If a sequence is monotone and bounded, then it converges.

**Proof:**
Let $(a_n)$ be monotone and bounded. Pick a candidate for the limit. Consider the set of points $\{a_n : n \in N\}$. By assumption, this set is bounded, so we can let
$$s = \sup\{a_n : n \in N\}$$
Claim that $\lim a_n = s$.
Let $\epsilon > 0$. Because $s$ is the supremum, $s-\epsilon$ is not an upper bound, so there exists a point in the sequence $a_N$ s.t. $a_N\leq a_n$. Hence, $$s-\epsilon<a_N\leq a_n\leq s<s+\epsilon$$
which implies $|a_n-s| < \epsilon$, as desired.