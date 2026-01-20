Assume $s \in R$ is an upper bound for a set $A \subseteq R$. Then, $s = \sup A$ iff $\forall \epsilon > 0 \space \exists a \in A$ s.t. $s-\epsilon < a$.
#### Proof:
- ($\Rightarrow$): Assume $s = \sup A, \epsilon > 0$. $s - \epsilon < s \longrightarrow s - \epsilon$ is not an upper bound for $A$.
- ($\Leftarrow$): Assume $s$ is an upper bound with the property that no matter how $\epsilon > 0$ is chosen, $s-\epsilon$ is no longer an upper bound for $A$. Any number smaller than $s$ cannot be an upper bound, so it follows that if $b$ is some other upper bound for $A$, then $s \leq b$.
