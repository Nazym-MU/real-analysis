Let $A \subseteq R$, nonempty and bounded above, and let $c\in R$. Define set $A$ by:
$$c + A = \{ c + a: a \in A\}$$
Then $\sup (c + A) = c + \sup A$.

Proof from the definition of [[Least upper bound|least upper bounds]]:
1. $s = \sup A$, so $a \leq s \space \forall \space a \in A \to c + a \leq c + s \space \forall \space a \in R$. Condition verified.
2. Let $b$ be an upper bound for $c + A$, i.e. $c+a \leq b \space \forall \space a \in A$.
	1. $a \leq b - c \space \forall \space a \in A$
	2. $s = \sup A \to s \leq b - c$
	3. $c + s \leq b$
	4. Condition verified.
Therefore, $\sup(c + A) = c + \sup A$. $\qquad \square$

