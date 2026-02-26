Consider $$\sum_{n=1}^\infty \frac{1}{n^2}$$
Because the terms are all positive, the sequence of partial sums is increasing: $$s_m = 1 + \frac{1}{4} + \frac{1}{9} + \dots \frac{1}{m^2}$$
Can we find some upper bound on $s_m$?
$$s_m = 1 + \frac{1}{2\cdot 2} + \frac{1}{3\cdot 3} + \dots \frac{1}{m^2} < 1 + \frac{1}{2\cdot1} + \frac{1}{3\cdot 2} + \dots \frac{1}{m(m-1)} = $$
$$=1 + \left( 1 - \frac{1}{2} \right) + \left(\frac{1}{2} - \frac{1}{3}\right) + \dots + \left(\frac{1}{(m-1)} - \frac{1}{m}\right) = 1 + 1 - \frac{1}{m} < 2$$
Thus, 2 is an upper bound for the sequence of partial sums. 