1. The union of an arbitrary collection of open sets is open.
2. The intersection of a finite collection of open sets is open.

**Proof:**
1. Let $\{O_\lambda: \lambda \in \Lambda \}$ be a collection of open sets. Let $O = \bigcup_{\lambda \in \Lambda} O_\lambda$. Let $a$ be an arbitrary element of $O$. Since $a \in O$, $a$ is in at least one $O_{\lambda'}$. Since $O_{\lambda'}$ is open, there exists $V_\epsilon (a) \subseteq O_{\lambda'}$. Since $O_{\lambda'} \subseteq O$, $V_\epsilon (a) \subseteq O$.
2. Let $\{O_1, O_2, \dots, O_N\}$ be a finite collection of open sets. If $a \in \bigcap_{k=1}^N O_k$, then $a$ is an element of each open set. Thus, $\forall \ k \in [1, N], \ \exists \ V_{\epsilon_{k}} (a) \subseteq O_k$. Take the smallest $\epsilon$-neighborhood that is contained in all $O_k$, i.e., $\epsilon = \min\{\epsilon_1, \epsilon_2, \dots, \epsilon_N\}$, it follows that $V_{\epsilon}(a) \subseteq V_{\epsilon_k} (a) \ \forall k$. Hence, $V_{\epsilon} (a) \subseteq \bigcap_{k=1}^N O_k$. $\square$

