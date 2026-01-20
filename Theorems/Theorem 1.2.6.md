Two real numbers a and b are equal if and only if for every real number $\epsilon > 0$, it follows that $|a - b| < \epsilon$
**Proof**
Iff means we work in two directions: 
- ($\Rightarrow$) If a = b, then for every real number $\epsilon > 0$, it follows that $|a - b| < \epsilon$
- ($\Leftarrow$) If for every real number $\epsilon > 0$ it follows that $|a - b| < \epsilon$, then we must have a = b

Forward: if a = b, then a - b = 0, so $|a -b| < \epsilon$
Backward: proof by contradiction: assume a $\neq$ b
Choose $\epsilon_0 = |a-b| > 0$
$|a-b| < \epsilon_0$ and $|a-b| = \epsilon_0$ cannot be both true. Therefore, a = b. $\square$
