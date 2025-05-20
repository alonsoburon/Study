In simple terms, the first derivative of a function is the slope of the function as it changes at a specific point.  Imagine walking along the curve of the function; the derivative tells you how steep the path is directly where you're standing.

## Slope of a linear function

For a linear function $f(x) = ax+b$ the slope or first derivative ignores the variable 'b' since where the slope is is not relevant for the angle of the slope.  The derivative of a linear function is simply the coefficient 'a', hence $m=a$.

## Slope of a function in general

For non-linear functions, the slope is generally not the same throughout all the function, meaning different values of $x$ have different slopes.
As such, the slope should be defined for each point across the slope.

To do this, we grab an infinitesimally small change in $x$, call it $dx$, loof for the slope of a tangent to that function.

Formally (when $f(x) = y$) it's defined as $$y' = \lim_{dx \to 0} \frac{(y+dy) - y}{dx}$$  

This expression calculates the slope of the secant line between two points on the curve,  $(x,y)$ and $(x + dx, y + dy)$

- Derivatives follow [[Derivation Rules|derivation rules]]

- Often, derivating is simpler when [[Function|functions]] are polynomials, for this we often use the example of the [[Taylor Series]] to approximate the function and then derive term by term.

## [[Partial Derivatives]]
These are simply derivatives used when you have multiple variables.