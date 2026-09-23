# Siacci's Equations and Ballistic Method

The method developed by Colonel Siacci of the Italian artillery is employed to calculate trajectories in cases of "high angle fire" (defined officially as fire at elevations greater than 15 degrees) and "curved fire" (fire from howitzers at all angles of elevation not exceeding 15 degrees). In these instances, the curvature of the trajectory is considerable, necessitating modifications to the formulae used for direct fire.

## Theoretical Foundation
Siacci's method begins with the exact equations of motion in a resisting medium:
*   $d^2x/dt^2 = -r \cos i = -r dx/ds$
*   $d^2y/dt^2 = -r \sin i - g = -r dy/ds - g$

By eliminating $r$, these reduce to the equation $di/dt = -\{g/v\} \cos i$. To simplify these integrations, which are otherwise intractable even with simple mathematical assumptions for the function $f(v)$ (such as quadratic or cubic laws), the method utilizes a principle originally pointed out by Euler. This principle observes that in ordinary trajectories, quantities such as $i$, $\cos i$, and $\sec i$ vary so slowly that they can be replaced by their mean values: $\eta$, $\cos \eta$, and $\sec \eta$. This is particularly effective if the trajectory is divided into arcs of small curvature.

## Pseudo-Velocity and Integration
To implement this, Siacci introduced the "pseudo-velocity" $u$, defined as $u = q \sec \eta$, where $q$ is the horizontal component of the velocity ($v \cos i = q$). The pseudo-velocity $u$ acts as a quasi-component parallel to the mean direction of the tangent, such as the direction of the chord of the arc.

Integrating from an initial pseudo-velocity $U$, the following relationships are established:
*   $\int_{u:U} du/f(u) = \int du/gp = T(U) - T(u)$
*   $\int u du/f(u) = S(U) - S(u)$
*   $\int g du/u f(u) = I(U) - I(u)$

## The Modified Equations
The equations (66)-(71) are attributed to Siacci, though they were slightly modified by General Mayevski. These equations allow for the application of ballistic tables designed for direct fire to be used in numerical applications for high angle fire:

*   **Time:** $t = C[T(U) - T(u)]$
*   **Horizontal distance:** $x = C \cos \eta [S(U) - S(u)]$
*   **Vertical distance:** $y = C \sin \eta [S(U) - S(u)]$
*   **Inclination change:** $\phi - \theta = C \cos \eta [I(U) - I(u)]$

In these equations, $\eta$ represents the inclination of the chord of the arc of the trajectory. While $\eta$ cannot be exactly the same mean angle in every equation, if it is the same for the $x$ and $y$ calculations, then $y/x = \tan \eta$.

## The Altitude-Function
Because a 1% variation in $\eta$ can cause more than a 1% variation in $\tan \eta$, calculating $\eta$ with high accuracy is difficult. Siacci addressed this by introducing the altitude-function $A$ or $A(u)$. This function allows $y/x$ to be calculated without introducing $\sin \eta$ or $\tan \eta$; instead, $\eta$ only appears as $\cos \eta$ or $\sec \eta$, which vary slowly for moderate values. Consequently, the arithmetic mean $1/2(\phi + \theta)$ is sufficient for $\eta$ over arcs of moderate extent.

The altitude-function $A$ is calculated via summation from the finite difference $\Delta A$, where $\Delta A = I(u) u[\Delta u] / gp = I(u)[\Delta S]$.

## Applications in Direct Fire
In the context of direct fire, the pseudo-velocities $U$ and $u$ are indistinguishable from the real velocities $V$ and $v$, and $\sec \eta$ can be replaced by unity. The altitude-function is used here to immediately determine the angle of descent ($\beta$) and the required angle of elevation ($\phi$) for a specific range. For small angles, these are expressed as:
*   $\sin 2\phi = 2C [I(V) - \Delta A/\Delta S]$
*   $\sin 2\beta = 2C [\Delta A/\Delta S - I(v)]$

## Sources
Compiled from: britannica11 vol02b baconthorpe to bankruptcy
---
*Written by the AI Librarian strictly from the public-domain books of the archive. Topic memory: data/written-topics.json*
