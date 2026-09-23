# Intractable Integrations and Integration Instruments

In the fields of mathematics and physics, the process of integration is used to determine values such as time, position, and angle. However, certain mathematical integrations are described as "quite intractable," meaning they are extremely difficult to solve, even when simple mathematical assumptions are applied to the functions involved.

## Intractability in Trajectory Calculations
In the study of trajectories, specific equations connect variables such as $q$ and $i$. The values for $t, x, y, i,$ and $\tan i$ are determined by integration with respect to $q$, provided that $\sec i$ is given as a function of $q$. These integrations remain intractable even when using simple mathematical assumptions for the function $f(v)$, such as a cubic law ($f(v) = v^3/k$) or a quadratic law ($f(v) = v^2/k$).

To overcome this difficulty, a method originally pointed out by Euler is employed. This approach recognizes that in ordinary trajectories, quantities such as $i, \cos i,$ and $\sec i$ vary so slowly that they can be replaced by their mean values ($\eta, \cos \eta,$ and $\sec \eta$). This is particularly effective if the trajectory is divided into arcs of small curvature, where curvature is defined as the angle between the normals or tangents at the ends of the arc. By replacing the angle $i$ with a mean value $\eta$, Siacci's pseudo-velocity $u$ is introduced, defined as $u = q \sec \eta$. This $u$ serves as a quasi-component parallel to the mean direction of the tangent, such as the direction of the arc's chord.

## Mechanical Integrators and Harmonic Analysers
Because some integrals are difficult to solve analytically, various mechanical instruments known as integrators have been developed to evaluate them.

### Harmonic Analysers
Harmonic analysers are instruments used to determine integrals of the form $A_n = 1/\pi \int_{0:2\pi} y \cos n\theta \, d\theta$ and $B_n = 1/\pi \int_{0:2\pi} y \sin n\theta \, d\theta$. These are used when $y$ is the ordinate of a curve and $\phi(x)$ is a simple function like $\sin nx$. 

The first such instrument was created by Lord Kelvin in 1876. In Kelvin's design, the curve is drawn on a cylinder with a circumference equal to the period $c$, and simple harmonic motion is used to introduce the sine and cosine terms. Other inventors, such as Sommerfeld and Wiechert of Konigsberg, modified this by turning the cylinder around an axis perpendicular to the cylinder's own axis. These machines are typically large fixtures.

### Other Integration Instruments
Amsler constructed an integrator that determines quantities by guiding a tracer around the boundary of a given figure. Other simple integrators function by using a templet of a curve $y' = \phi(x)$ to determine the area of the curve. By varying distances to form another curve $y'' = f(x)$, the instrument can obtain integrals of the form $\int_{0:c} f(x) \phi(x) \, dx$. These results are obtained through the addition of ordinates; while this is an approximate method, the use of numerous ordinates (such as 79) ensures high accuracy. If the points are set proportional to a numerical series, the device can function as an Addition Machine.

## Theoretical Integration in Multiple Dimensions
In mathematical physics, the integral of a function $f(x)$ through a measurable domain $H$ (a homogeneous part of a numerical continuum of $n$ dimensions) is defined similarly to an integral through an interval. A primary condition for integrability is that the function remains continuous throughout the domain.

Special considerations are made for "improper" definite integrals. If a function tends toward infinity at a specific point in the domain, that point is enclosed in a partial domain which is omitted, and a limit is taken as the omitted domain is diminished indefinitely. This can lead to divergent integrals, which may have different principal values depending on how the omitted partial domain is contracted. These principal values are critical in mathematical physics; for example, the component of magnetic induction and the component of magnetic force at a point within a magnet are expressed by different principal values of the same divergent integral.

## Complex Variable Integration
Integration also extends to functions of a complex variable. This involves the establishment of the complex integral and the application of Cauchy's theorem. Further applications include the integration of series of functions of a complex variable and the use of Laurent's theorem. This theoretical framework leads to the definition of singular points and the region of existence for a function, as well as the study of monogenic functions as defined by Weierstrass.

## Sources
Compiled from: britannica11 vol02b baconthorpe to bankruptcy, britannica11 vol05a bulgaria to calgary, britannica11 vol09a frost to fyzabad
---
*Written by the AI Librarian strictly from the public-domain books of the archive. Topic memory: data/written-topics.json*
