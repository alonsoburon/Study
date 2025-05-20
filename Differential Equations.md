
The relationship between an unknown function and its derivatives, it's done through Integration and use of the integration constants.
It's used for modelling in mechanics, thermodynamics and multiple other sciences, including economy and physics.

Algebraically it's complicated to solve, and **numerical methods** are often necessary.

The amount of derivatives present are what gives each equation its **order**, the prescence of $y''$ would make it a second-degree equation. 

## First Order differential equations
$$ 
y'(x) + f(x)y(x) = g(x)
$$

These are further subdivided by the value of $g(x)$, if its $0$ then it's a homogeneous equation.  Otherwise it's a non-homogeneous equation.

$f(x)$ and $g(x)$ **can** be constants ($C$) with a defined value, or be dependent on $x$.

### General solution

1) Isolate the $y$'s $$\begin{align*}
y' + f(x)y & = 0 \\
y' & = -f(x)y \\
\frac{y'}{y} & = -f(x)
\end{align*}$$
2) Integrate both sides of the equation with respect to  $x$:

$$\int \frac{y'}{y} dx = \int -f(x) dx$$

This yields:

$$\ln|y| = - -F(x) + C$$ 

where $F$ is the anti-derivative or primitive function, and $C$ is the constant of integration.

3) Exponentiating both sides yields the general solution: 

$$y = e^{-F(x) + C} $$

This can be further simplified as : 

$$y = e^C \cdot e^{-F(x)} $$
 
Since $e^C$ is itself an arbitrary constant, it can be replaced with another constant, $a$

### Homogeneous differential equation
If we restrict ourselves to the simpler case where $f(x)$ = $c$,
then $$ y' + cy = 0
$$
And as such, $F(x) = cx$ and $$ y=a \cdot e^{-cx} $$
### Particular/Specific/Special solution
In order to select one function, we need more information, specifially the initial value for $x$.

if $x=0$...
$$\begin{align*}
y(0) &= y_0 \\
y(x) &= a \cdot e^{-cx} \\
y_0 &= a \cdot e^{-c \cdot 0} \\
y_0 &= a \cdot 1 \\
y_0 &= a
\end{align*}$$

Once the value of $a$ is determined, we have a specific solution to the differential equation that satisfies the given initial condition. Therefore, if  $x = 0$ and $y(0) = y_0$,  the particular solution becomes: $$y = y_0 \cdot e^{-cx}$$ 
### Non-homogeneous differential equations

In these cases you have an equation shaped like $y' + cy = s$

1) Find the general solution to its corresponding homogeneous equation ($s=0$), let's call it $g(x)$
2) Find **any** particular solution to the non-homogeneous equation, let's call it $s(x)$
	1) For this, try defining an $s$ such that $y'$ will be $0$.
3) The solution will be the sum of both solutions, meaning $$ y = g(x) + s(x) $$
4) If we also have an initial condition $y_0$, then we can get this particular solution.

## Population growth

$$ y'(t) = cy(t) $$

Where $y$ represents the amount of population and $y'$ its first derivative, growth.

Whenever there's an upper limit $K > 0$ then $y' = c(K-y)$ which translates into
$$ y' + cy = cK $$
We can then define a particular solution to the equation as K (since its a straightforward algebraic manipulation to find y'.  This gives us a particular solution of the form $y = K$ such that finally:

$$ y(t) = ae^{-ct}+ K$$
Then by knowing the initial condition $y_0$ we can calculate a with $a = y_0 - K$ and finally find the particular solution to the non-homogeneous equation.

$$\Huge{
y(t) = (y_0 - K) \cdot e^{-ct} + K
}$$

## Newton's Law of Cooling

For $T_t$ being Temperature, and $T'_t$ being change of temperature, and $T_{env}$ being the environment temperature. k being the cooling constant. Then, Newton's Law of Cooling states: 

$$ \Huge {
T'_t - kT_t = -kT_{env}
}$$

This differential equation describes how the temperature of an object changes over time as it cools down towards the ambient temperature.


