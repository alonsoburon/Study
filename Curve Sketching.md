The analysis of behaviour of a [[function]].

![[Pasted image 20250518141853.png]]

It involves identifying multiple values, such as
- Definition and value range
- Symmetry
- Zeros (or Roots)
- Pole points
- Asymptotic behaviour
- Monotonicity
- Extreme values (Minima and Maxima)
- Inflection points and Saddle Points.

## Definition
Simply check the value ranges of the Domain and Codomain.
## Symmetry
Check $f(-x)$ and $-f(x)$:
- If $f(-x) = f(x)$ then the function is symmetrical on the $y$-axis, and its first derivative $f'(x)$ is symmetrical to the origin
- If $f(-x) = -f(x)$ then the function is symmetrical to the origin, and its first derivative $f'(x)$ is symmetrical to the $y$-axis

## Zero points (Roots)
For this, you solve the equation for $f(x) = 0$ Generally, this involves using techniques like factoring, the quadratic formula, or numerical methods to find the value or values of $x$ that satisfy the equation.

## Pole points
These only show up in fractions, roots and logarithms, and are points where the function approaches infinity. To find them, look for values of *x* that make the denominator of a fraction zero, or the argument of a logarithm zero. 
![[Pasted image 20250518144053.png]]
> In this case, the root would be at $x=3$ since the denominator cannot be $0$.
## Asymptotic behaviour

Determine if the function approaches a specific value (horizontal asymptote) as *x* approaches positive or negative infinity. Also check for vertical asymptotes by examining where the function approaches infinity as *x* approaches certain values.

## [[Monotonicity]]

Whenever the monotonicity changes **locally**, its called a *monotonicity change* and its this splits our function into ranges of $f(x)$ where the function is either strictly increasing or strictly decreasing.

The *slope* can now be thought as the first derivative $f'(x)$ and if its value is greater or lesser than 0 will represent if its monotonically increasing or decreasing.

## Extreme values
Find the roots of the first derivative, meaning points where $f'(x) = 0$ and then check the second derivative at each of those points, let's call them $r$.
- $f''(r) < 0$ then $r$ is a *maximum*.
- $f''(r)>0$ then $r$ is a *minimum*.

## Turning (Inflection) points
Whenever the roots of the second derivative $f''(x) = 0$ then we're at an inflection point, these can be categorized using the third derivative for each root $r$.

$f'''(r) \neq 0$ then $r$ is a **turning** point

else if $f'''(r) = 0$ then $r$ is a **saddle** point

These occur when the second derivative changes sign  around a critical point (a point where the first derivative is zero). Essentially, at a saddle point, the function transitions from being locally concave up to locally concave down, or vice versa.

