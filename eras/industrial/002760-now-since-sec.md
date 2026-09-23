# The Equation v = g sec i and Siacci's Method

The equation $v = g \sec i$ serves as a foundational component in the mathematical analysis of trajectories, specifically within the context of calculating the path of a projectile. This relationship is utilized to derive various equations connecting velocity, angle, and distance, and it forms the basis for simplifying complex integrations through the application of Siacci's method.

## Derivations and Integration
In the study of trajectories, the equation $v = g \sec i$ is used to establish several differential relationships. These include an equation connecting $q$ and $i$, as well as the following derivations:
*   $dt/dq = -C \sec i / f(q \sec i)$
*   $dx/dq = -C q \sec i / f(q \sec i)$
*   $dy/dq = -C q \sec i \tan i / f(q \sec i)$
*   $di/dq = Cg / \{q \sec i \cdot f(q \sec i)\}$
*   $d \tan i/dq = C g \sec i / \{q \cdot f(q \sec i)\}$

Through these, the values for $t, x, y, i,$ and $\tan i$ can be determined by integration with respect to $q$, provided that $\sec i$ is given as a function of $q$. However, these integrations are considered quite intractable, even when using simple mathematical assumptions for the function $f(v)$, such as a cubic law ($f(v) = v^3/k$) or a quadratic law ($f(v) = v^2/k$).

## Siacci's Pseudo-Velocity and Mean Values
To resolve the difficulty of these intractable integrations, a method originally pointed out by Euler is employed. This approach recognizes that in ordinary trajectories, the quantities $i, \cos i,$ and $\sec i$ vary slowly enough to be replaced by their mean values: $[\eta], \cos [\eta],$ and $\sec [\eta]$. This is particularly effective if a considerable trajectory is divided into arcs of small curvature, where curvature is defined as the angle between the normals or tangents at the ends of the arc.

By replacing the angle $i$ on the right-hand side of the primary equations with the mean value $[\eta]$, Siacci's pseudo-velocity $u$ is introduced, defined as:
$u = q \sec [\eta]$

In this context, $u$ acts as a quasi-component parallel to the mean direction of the tangent, such as the direction of the arc's chord. Consequently, $[\eta]$ represents the inclination of the chord of the trajectory arc.

## Application to High Angle Fire
When applying Siacci's method to high angle fire trajectories via successive arcs of small curvature, the process begins at an arc starting at angle $[\phi]$ with velocity $v_{[\phi]}$. The curvature of the arc $[\phi] - [\theta]$ is determined, and a first approximation for the mean value is established as $[\eta] = 1/2([\phi] + [\theta])$.

The pseudo-velocity $u_{[\phi]}$ is then calculated using the formula:
$u_{[\phi]} = v_{[\phi]} \cos [\phi] \sec [\eta]$

From the given values of $[\phi]$ and $[\theta]$, the final pseudo-velocity $u_{[\theta]}$ can be calculated using specific formulae:
*   $I(u_{[\theta]}) = I(u_{[\phi]}) - \{\tan [\phi] - \tan [\theta]\} / \{C \sec [\eta]\}$
*   $D(u_{[\theta]}) = D(u_{[\phi]}) - \{[\phi]deg - [\theta]deg\} / \{C \cos [\eta]\}$

## Trajectory Calculations and the Altitude-Function
The method allows for the calculation of time, distance, and the ratio of $y/x$ over an arc:
*   The time interval is given by $[\phi]t_{[\theta]} = C[T(u_{[\phi]}) - T(u_{[\theta]})]$.
*   The distance is given by $[\phi]x_{[\theta]} = C \cos [\eta] [S(u_{[\phi]}) - S(u_{[\theta]})]$.
*   The ratio is given by $[\phi](y/x)_{[\theta]} = \tan [\phi] - C \sec [\eta] [I(u_{[\phi]}) - \Delta A/\Delta S]$.

To avoid the need for high accuracy in calculating $[\eta]$—since a 1% variation in $[\eta]$ can cause more than a 1% variation in $\tan [\eta]$—Siacci's altitude-function $A$ or $A(u)$ is used. In this function, $[\eta]$ only appears as $\cos [\eta]$ or $\sec [\eta]$, which vary slowly for moderate values of $[\eta]$. The altitude-function $A$ is calculated via summation from the finite difference $\Delta A$, defined as $\Delta A = I(u) u\Delta u / gp = I(u)\Delta S$.

## Sources
Compiled from: britannica11 vol02b baconthorpe to bankruptcy
---
*Written by the AI Librarian strictly from the public-domain books of the archive. Topic memory: data/written-topics.json*
