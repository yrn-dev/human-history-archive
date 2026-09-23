# General Notion of Functionality and Types of Functions

## General Notion of Functionality
Historically, a function of one variable was commonly viewed as the ordinate of a curve. For a significant period, mathematicians did not clearly distinguish between a function determined by a drawn curve and one determined by a written analytical expression. This distinction became critical following Fourier's discovery that a single analytical expression could represent what were previously considered different functions across different parts of an interval.

The general notion of functional dependence is defined by a variable number $y$, another variable number $x$ (the argument), a domain for $x$, and a rule for assigning one or more definite values to $y$ whenever $x$ is any point in that domain. Under this definition, a function is comparable to an indefinitely extended table, such as a table of logarithms, where the values the function takes at any point in the domain remain arbitrary.

## Ordinary and Analytic Functions
A function is classified as "ordinary" if it can be represented by a curve (its graph) that possesses specific properties:
1. The coordinates of a point on the curve are the value $x$ of the argument and the corresponding value $y$ of the function.
2. The curve has a definite tangent at every point.
3. The interval can be divided into a finite number of partial intervals where the function is monotonous.
4. This monotony is retained even after the $x$ and $y$ axes of coordinates are interchanged.

While condition (2) implies that $y$ is a continuous and differentiable function of $x$, it does not guarantee conditions (3) and (4). Consequently, there are continuous differentiable functions that are not monotonous in any interval, and continuous, differentiable, and monotonous functions that fail to satisfy condition (4). 

A function is termed "analytic" when Taylor's theorem allows it to be represented by an infinite series. While all analytic functions are ordinary, not all ordinary functions are analytic.

## Differentiable and Integrable Functions
The differentiation of a continuous function is a process used to measure the rate of growth by comparing the increment of the function with the increment of the variable. For a function $f(x)$ defined in an interval containing point $a$, the expression $\frac{f(a+h) - f(a)}{h}$ represents a function $\phi(h)$. This leads to four limits known as the "four derivates" of $f(x)$ at $a$, named after Dini. These are denoted as $f'_+(a)$, $f'_+(a)$, $f'_-(a)$, and $f'_-(a)$. If the first two are equal, the result is the "progressive differential coefficient"; if the last two are equal, it is the "regressive differential coefficient." When all four are equal, the function is "differentiable" at $a$, and the result is the "differential coefficient" or "first derived function," denoted by $f'(x)$ or $\frac{df(x)}{dx}$.

Integration is approached in two ways: seeking a function that has a given function as its differential coefficient (the indefinite integral) or generalizing the finding of the area of a curve (the definite integral). Riemann defined the definite integral of $f(x)$ through an interval between $a$ and $b$ as the limit of the sum $\sum [f](x'_r)(x_r - x_{r-1})$. A function is "integrable" in an interval if it is defined for all points without tending toward infinity, and if the sum of the products of the oscillation of the function in each partial interval and the difference of the end-values has a limit of zero as $n$ increases indefinitely. Any continuous function is integrable.

## Monotony and Limits
A function $f(x)$ is "increasing throughout the interval" if $f(x') > f(x)$ whenever $x' > x$. It "never decreases" if $f(x') \geq f(x)$. Conversely, functions may be decreasing or "never increase." A function that either never increases or never diminishes is "monotonous throughout" the interval. If a function is monotonous within an interval (excluding the endpoints), it has a limit on the left at the upper limit $b$ and a limit on the right at the lower limit $a$.

A function $f$ has a limit at $a$ if, for any positive $\epsilon$, there is a corresponding $h$ such that $|f(x') - f(x)| < \epsilon$ for any two points $x, x'$ in the neighbourhood of $a$ (excluding $a$ itself). For functions of $n$ variables, a "limit at an infinite distance" exists if, for any $\epsilon$, a number $N$ can be found such that $|f(x') - f(x)| < \epsilon$ for all points where one or more coordinates exceed $N$ in absolute value.

## Representation and Complex Variables
The problem of representation involves determining a single analytical expression that matches a function's value at all points in its domain. This often requires limiting processes, such as infinite products, definite integrals, or infinite series. In the case of series, the sum represents a function within its "domain of convergence."

When complex or imaginary quantities are involved, the theory extends to the complex plane. This includes the study of:
* **Complex numbers** and their plotting via conformal representation.
* **Limiting operations** used to define the exponential function and the generalized logarithm $\lambda(z)$.
* **Monogenic functions**, with the simplest definition provided by Weierstrass.
* **Singular points** and the region of existence of a function.
* **Single valued functions**, where a function with only poles is rational.

Note: the archive's sources are limited for this topic.

## Sources
Compiled from: britannica11 vol09a frost to fyzabad
---
*Written by the AI Librarian strictly from the public-domain books of the archive. Topic memory: data/written-topics.json*
