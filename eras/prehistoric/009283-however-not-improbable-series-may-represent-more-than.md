# Geological and Mathematical Series

The term "series" appears across diverse academic disciplines, ranging from the geological composition of the Andes to the representation of functions in mathematical analysis.

## Geological Series of Bolivia
In the geology of Bolivia, series refer to specific sequences of rock layers. The eastern ranges of the Bolivian Andes are composed of Palaeozoic rocks with other intrusions, including granitic ones. These Palaeozoic beds have yielded fossils from the Carboniferous, Devonian, Ordovician, and Cambrian ages. In the north-eastern ranges, the Devonian and Carboniferous are extensively developed, while the Cambrian and Ordovician beds form the majority of the eastern Andes in the south.

Directly overlying these Palaeozoic beds is a series of gypsiferous marls and red sandstones, which are similar to the *formacion petrolifera* found in Brazil and Argentina. This series frequently features a tuff or conglomerate of porphyritic rocks at its base. Gustav Steinmann identified marine fossils in the middle of this series, which he referred to the Lower Cretaceous, indicating an age no earlier than the Jurassic. It is considered not improbable that this specific series may represent more than one geological system.

## Representation of Functions by Mathematical Series
In mathematics, infinite series are utilized as limiting processes to represent functions. When the terms of a series are functions of a variable $x$, the sum of the first $n$ terms ($s_n$) is a function of $x$ and $n$. If the series is convergent, its sum represents a function of $x$ within a "domain of convergence."

### Power Series
A power series is an infinite series where the general term is $a_n z^n$ ($n = 0, 1, 2, 3, \dots$) and $a_n$ is a constant. Every power series has a circle of convergence within which it converges uniformly and absolutely. The function represented by such a series is continuous within this circle.

If a power series converges at any point other than $a$, there exists a number $k$ such that the series converges absolutely between $a - k$ and $a + k$ (potentially excluding one or both endpoints). Such a series represents an analytic function in its domain of convergence and is the Taylor's series for that function.

### Fourier and Continuous Functions
Continuous functions can be represented with arbitrarily close approximation using "terminated power series" or "terminated Fourier's series." For a function $f(x)$ continuous between $0$ and $2\pi$, and for any specified positive number $\epsilon$ however small, an integer $n$ can be found such that the difference between $f(x)$ and the sum of the first $n$ terms of the Fourier series is less than $\epsilon$ at all points of the interval. However, P. du Bois Reymond proved that a function may be continuous at a point $a$, yet the series formed by Fourier's rule may be divergent at that point.

## Convergence and Divergence
The behavior of a series in its interval or region of existence determines its utility and the nature of the function it represents.

### Uniform Convergence
The relationship between convergence and continuity is defined by several theorems:
1. A series that converges uniformly in an interval represents a function that is continuous throughout that interval.
2. If a series represents a function that is discontinuous in an interval, it cannot converge uniformly in that interval.
3. A series may represent a function that is continuous throughout an interval even if it does not converge uniformly.

For example, the series $\sin x - 1/2 \sin 2x + 1/3 \sin 3x - \dots$ converges for all real values of $x$ and sums to $1/2x$ when $\pi > x > -\pi$. However, as $x$ approaches $\pi$, the number of terms required to bring the sum near $1/2x$ increases indefinitely, meaning the series does not converge uniformly in the neighbourhood of $x = \pi$.

### Asymptotic Expansions
When series diverge, they may still be used for approximate numerical calculations if the calculation is not carried beyond a certain number of terms. These are known as "asymptotic expansions" or "semi-convergent series." In such cases, for a specified small $\epsilon$, a number $n$ can be found so that the value of a function $f(a)$ is connected to the sum of the first $n+1$ terms by the relation $|f(a) - \sum_{r=0}^{n} f_r(a)| < \epsilon$. Simultaneously, for any large number $N$, a number $n' > n$ can be found such that for all $m > n'$, $|\sum_{r=0}^{m} f_r(a)| > N$.

## Monogenic and Analytical Functions
A function can be defined by an aggregate of power series where each series has points of convergence common with one or more others. By continuing the process of analytical continuation—where a series is rearranged in powers of $z - z_0$ about a point interior to its circle of convergence—one reaches the "region of existence" of the function. The limiting points of this region, where the radii of convergence of derived series diminish to zero, are the singular points. A function defined this way is called a monogenic function, a monogenic analytical function, or simply an analytical function.

## Sources
Compiled from: britannica11 vol03b bohemia to borgia, britannica11 vol09a frost to fyzabad, grote history of greece v01
---
*Written by the AI Librarian strictly from the public-domain books of the archive. Topic memory: data/written-topics.json*
