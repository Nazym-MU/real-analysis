> Given any set $A$, there does not exist a function $f: A \to P(A)$ that is onto.

Proof:

Assume, for contradiction, that $f: A \to P(A)$ is onto. For each element $a \in A, f(a)$ is a particular subset of $A$. Given the assumption that $f$ is onto means that every subset of $A$ appears as $f(a)$ for some $a \in A$.

We will produce a subset $B \subseteq A$ that is not equal to $f(a)$ for any $a \in A$. For each $a \in A$, consider the subset $f(a)$. If $f(a)$ does not contain $a$, then we include $a$ in our set $B$. More precisely, let $$B = {a \in A: a \notin f(a)}$$

Because we assumed that the function is onto, it must be that $B = f(a')$ for some $a' \in A$. The contradiction arises when we consider whether or not $a'$ is an element of $B$. 