For each $n \in N$, assume we are given a closed interval $I_n = [ a_n, b_n ] = \{ x \in R: a_n \leq x \leq b_n \}$. Assume also that each $I_n$ contains $I_{n+1}$. Then, the resulting nested sequence of closed intervals $I_1 \supseteq I_2 \supseteq I_3 \supseteq I_4 \supseteq ...$ has a nonemtpy intersection; that is $\bigcap_{n=1}^\infty I_n \neq \emptyset$. 

**Proof:**
Use [[Axiom of completeness]] (AoC) to produce a single number $x$ satisfying $x \in I_n$ for every $n \in N$. Consider the set $A = \{a_n: n \in N\}$ of lefthand endpoints of the intervals.
Because intervals are nested, every $b_n$ serves as an upper bound for $A$. Thus, $x = \sup A$.
Consider a particular $I_n = [a_n, b_n]$. Because x is an upper bound for $A$, we have $a_n \leq x$. Each $b_n$ is an upper bound for $A$ and $x$ is the least upper bound. This implies that $x \leq b_n$.
We have $a_n \leq x \leq b_n$, which means $x \in I_n$ $\forall$ $n \in N$. Hence, $x \in \bigcap^\infty_{n=1} I_n$ and the intersection is not empty. $\square$

Only guarantees that there is a real number, not necessarily rational. That's why it doesn't work for $\mathbb Q$
