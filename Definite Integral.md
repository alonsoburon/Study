
The area $A$ between the function $f(x)$ and the $x$ axis can be calculated using the [[Function|Primitive Function]] $F(x)$ of $f(x)$. Then evaluating on the 2 edge points of the function and then substracting from them.

$$
A = \int_{a}^{b} f(x)\, dx = F(x)\bigg|_{a}^{b} = F(b) - F(a)
$$

```functionplot
---
title: Área bajo la curva entre a y b
xLabel: x
yLabel: y
bounds: [1, 9, 0, 2]
disableZoom: true
grid: true
---
f(x)= 2 + sin(x) - 0.2*(x - 5)^2
```


This can then be used to calculate 2 values, the [Definite Integral] or the [Area between the functions and axes].

## Definite Integral
Also named "signed area", it represents the value of the area by considering contributions below the $x$ axis as negative, an as such substracting from the area.

To calculate this, it's as simple as integrating and getting the result.

## Area between the functions and axes
This grabs the sum of the **absolute values** of each section of the integral.

For this, you have to find the roots of the function and split each interval, then use the absolute value for each interval.

> Definite integral: $A_1+A_2+A_3+A_4$
> Area: $|A_1|+|A_2|+|A_3|+|A_4|$

## Calculating the area without a given interval

- Between a function and the $x$ axis:
	- Find the roots or intersections with the $x$ axis
- Between 2 functions:
	- Find the roots of their difference between both funcitions ($f(x)-g(x) = 0$)

## Rotational solids

A rotational solid or solid of revolution comes about when a positive function projects its rotation around the $x$ axis, making the surface of the object the surface of points $f(x)$ distance away from the $x$ axis.

### Arc Length
$$ L = \int _a ^b \sqrt{1+f'(x)^2}dx$$

### Volume
$$ V = \pi \int _a ^b f(x)^2 dx $$
### Lateral surface
$$ M = 2\pi \int _a ^b f(x) \sqrt{1+f'(x)^2} dx $$