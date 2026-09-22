# Ballistic Functions T, S, D, I, and A

In the study of ballistics, specifically regarding the motion of a shot, several numerical functions are utilized to calculate the trajectory and characteristics of a projectile. These functions—T, S, D, I, and A—are presented numerically in abridged ballistic tables. In such tables, velocity serves as the argument and increases by increments of 10 f/s. While the column for p is determined through experiment, the remaining columns are derived via calculation.

## The Functions I and D
The functions I and D relate to the inclination of the projectile's motion. If $v$ represents the mean velocity during a small finite interval of time ($\Delta t$) in which the direction of motion changes by $\Delta i$ radians, the change in inclination in degrees ($\Delta \delta$) is expressed as:
$$\Delta \delta = \frac{180}{\pi} \Delta i = \frac{180g}{\pi} \frac{\Delta t}{v}$$

When these variables are applied to a standard projectile, $\delta$ and $i$ change to D and I respectively. The differences are calculated as follows:
*   $\Delta I = \frac{g \Delta T}{v} = \frac{\Delta v}{vp}$
*   $\Delta D = \frac{180g}{\pi} \frac{\Delta T}{v}$

The values for $D(v)$ and $I(v)$ are obtained through summation using an arithmometer and are then entered into their respective columns. Furthermore, the relationship between the two is defined such that $D(V) - D(v) = \frac{180}{\pi} [I(V) - I(v)]$. In instances of direct fire, where $i$ is small, it is sometimes preferable to maintain the circular measure of $i$ radians, as it is undistinguishable from $\tan i$ and $\sin i$.

## The Altitude Function A
The function A is designated as the "altitude function." Its specific application and explanation are reserved for the consideration of high angle fire.

## Table Initialization
For the purposes of ballistic calculation, the initial values for the functions T, S, D, I, and A are accepted as belonging to the anterior portion of the ballistic table.

## Sources
Compiled from: britannica11 vol02b baconthorpe to bankruptcy
---
*Written by the AI Librarian strictly from the public-domain books of the archive. Topic memory: data/written-topics.json*
