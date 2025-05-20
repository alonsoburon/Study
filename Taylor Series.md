Taylor series are a special type of infinite [[series]] that represent functions as a sum of terms.

It's often written as $$ 
a_0 + a_1(x) + a_2(x)^2 + a_3(x)^3 + ...$$
where $a_i$ are coefficients determined by the [[function]].

If a complex function can be [[Derivatives|diferentiated]] infinitely, then it can be represented by a Taylor series centered at any point within its domain of differentiability. Where each $a_i$ represents the $i-$th derivative of the function

They can also be centered not only around 0 but an arbitrary number, by changing 
$$\sum _{k=0} ^{\infty} a_k \cdot x^k
\quad \text{to} \quad
\sum _{k=0} ^{\infty} a_k \cdot (x-a)^k$$

For getting the Taylor series of a specific [[function]], you simply need to calculate its derivatives at the chosen center point and plug them into the appropriate formula.
$$\text{Taylor}_{(x,c)} = \sum_{k=0}^{\infty} \frac{f^{(k)}(c)}{k!}(x-c)^k$$