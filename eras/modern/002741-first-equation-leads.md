# Equations in Physical and Mathematical Systems

The use of equations to describe the behavior of physical systems, celestial bodies, and mathematical projections is a fundamental aspect of analytic methods. By defining positions through coordinate axes and constructing differential equations to express changes in those coordinates, the laws of motion and equilibrium can be discovered through integration.

## Celestial Mechanics and Planetary Motion
In the study of celestial mechanics, the motion of a planet—considered as a material particle—around a center of attraction is governed by the law of Newton. While actual problems in this field require three coordinates, leading to three differential equations and six equations of solution, the general principles are exemplified using two bodies. In this simplified case, motion occurs in a fixed plane (the plane of the orbit), utilizing two coordinates, $x$ and $y$, relative to the sun as the origin.

The distance between the sun (mass $M$) and the planet (mass $m$) is the radius vector $r$, defined by the equation $r^2 = x^2 + y^2$. The motion of the planet relative to the sun is completely determined by the following differential equations:
- $d^2x/dt^2 = -(M + m)x / r^3$
- $d^2y/dt^2 = -(M + m)y / r^3$

If the position $P$ of a planet is known at a specific moment, along with its velocity and direction, the orbit is completely determined. Analytically, the elements of the orbit ($a, b, c, d$) are found by solving four equations where $x, y, x', y',$ and $t$ are given quantities.

## Ballistics and Trajectory Equations
In the calculation of range tables for "direct fire"—defined as fire from guns with full charge at an elevation not exceeding 15 degrees—the vertical component of air resistance is considered insensible. In these instances, the equations of motion, with coordinates $x$ and $y$ measured in feet, are:
- $d^2x/dt^2 = -r = -gp/C$
- $d^2y/dt^2 = -g$

The first equation leads to expressions for time ($t = C\{T(V) - T(v)\}$) and distance ($x = C\{S(V) - S(v)\}$). Integration of the second equation provides the formula for $y = 1/2gt(T - t)$, where $T$ is the total time of flight from point $O$ to point $B$. Using $g = 32\text{f/s}^2$, this is expressed as Colonel Sladen's formula, $y = 16tt'$. At the vertex $A$ of the trajectory, where $y = H$ and $t = 1/2T$, the height is determined by $H = 1/8gT^2$, which for practical purposes is replaced by $H = 4T^2$ or $(2T)^2$.

## Fluid Lubrication and Equilibrium
The equilibrium of a lubricant is described by differential equations of viscous fluid in steady motion, subject to specific conditions: the velocity must be below a critical value, the fluid velocity at the surfaces must match the solid's velocity, and the film thickness must be small relative to the radii of curvature and lateral dimensions of the surfaces.

Under these conditions, terms involving $\rho$ are neglected. By further omitting terms depending on compressibility and treating $\mu$ as a constant, the differential equation for the equilibrium of the lubricant is established. Further differentiation and integration regarding $x$ and $z$ lead to the general equations for normal pressure ($p$) and tangential stresses ($f_x, f_z$) at the boundaries.

## Mathematical Projections and Periodic Functions
Equations are also used to translate spherical surfaces into flat maps. In Mercator's Projection, the equator is a straight line and meridians are equidistant straight lines. The distance of a parallel of latitude $\phi$ from the equator is expressed as $r = a \log_e \tan(45^\circ + 1/2\phi)$, or as a series: $r = a(\sin \phi + 1/3 \sin^3\phi + 1/5 \sin^5\phi + \dots)$. This projection is orthomorphic, meaning it retains the similarity of representation for small parts of the surface. Consequently, a loxodromic curve (a curve cutting all meridians at the same angle) is projected as a straight line.

In higher mathematics, equations are used to define periodic functions. For example, the Sigma-function $\sigma(z)$ is determined via an integral function and satisfies specific equations involving constants $\eta$ and $\eta'$. These functions are used to analyze poles in the plane of $u$ and the radii of convergence for expansions.

## Chronological Equations
The archive also notes the occurrence of solar and lunar equations used in timekeeping. Solar equations occur in years such as 1700, 1800, 1900, 2100, 2200, 2300, and 2500. Lunar equations occur in years including 1800, 2100, 2400, 2700, 3000, 3300, 3600, and 3900. When a solar equation occurs, epacts are diminished by unity; when a lunar equation occurs, they are augmented by unity. If both occur simultaneously (e.g., 1800, 2100, 2700), they compensate for each other and the epacts remain unchanged.

## Sources
Compiled from: britannica11 vol04a arundel to athens, britannica11 vol02b baconthorpe to bankruptcy, britannica11 vol09a frost to fyzabad, britannica11 vol17a lord chamberlain to luqman, britannica11 vol05a bulgaria to calgary, britannica11 vol17c map to mars
---
*Written by the AI Librarian strictly from the public-domain books of the archive. Topic memory: data/written-topics.json*
