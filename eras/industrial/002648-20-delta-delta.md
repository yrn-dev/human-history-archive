# $\Delta i / \Delta t = g/v$

The expression $\Delta i / \Delta t = g/v$ is a formula used in the study of ballistics to determine the change in the direction of motion of a projectile. It is a simplified derivation used specifically for problems of direct fire, where the trajectory of the shot is sufficiently flat.

## Theoretical Basis
The theory behind this calculation is detailed in the "degree table" attributed to Sir W. D. Niven, F.R.S. This table is designed to determine how the direction of motion of a shot changes as its velocity decreases from an initial velocity $V$ to a final velocity $v$, assuming the shot is flying nearly horizontally.

To establish the theory, the tangent at a specific point on the trajectory—where the velocity is $v$—is assumed to make an angle of $i$ radians with the horizon. By resolving normally in the trajectory and assuming that the resistance of the air acts tangentially, the relationship is expressed as $v(di/dt) = g \cos i$. In this context, $di$ represents the infinitesimal decrement of $i$ over an infinitesimal increment of time $dt$.

## Application in Direct Fire
In scenarios involving direct fire, the trajectory is considered flat enough that $\cos i$ is undistinguishable from unity. Under these specific conditions, the equation $v(di/dt) = g \cos i$ simplifies to $v(di/dt) = g$, which can be rewritten as $di/dt = g/v$. Consequently, the relationship is expressed as:
$$\Delta i / \Delta t = g/v$$
where $v$ denotes the mean velocity during a small finite interval of time $\Delta t$, during which the direction of motion of the shot changes through $\Delta i$ radians.

## Integration into Ballistic Tables
The value $\Delta i$ can be converted from radians to degrees (denoted as $\Delta \delta$) using the relationship $\Delta \delta / 180 = i / \pi$. This allows the change in inclination to be calculated as $\Delta \delta = 180g / \pi \Delta t / v$.

For a standard projectile, these values are represented as $\Delta I$ and $\Delta D$. The change in direction is calculated as:
*   $\Delta I = g \Delta T / v = \Delta v / vp$
*   $\Delta D = 180g / \pi \Delta T / v$

The total change in direction between an initial velocity $V$ and a final velocity $v$ is found by the summation or integration of these values:
*   $I(V) - I(v) = \sum_{v:V} \Delta v / vp$ or $\int_{v:V} dv / vp$
*   $D(V) - D(v) = 180 / \pi [I(V) - I(v)]$

These differences are calculated and the resulting values for $D(v)$ and $I(v)$ are obtained via summation with an arithmometer and entered into ballistic tables. In direct fire, it is often preferable to retain the circular measure ($i$ radians), as it is undistinguishable from $\sin i$ and $\tan i$ when $i$ is small.

## Related Ballistic Functions
The function $I$ is part of a larger set of numerical functions used in abridged ballistic tables, which include $T$ (time), $S$ (advance), $D$ (degree), $I$ (inclination), and $A$ (the altitude function). In these tables, velocity is used as the argument, typically proceeding by increments of 10 f/s. The calculations for these functions rely on the value of $p$, which is determined experimentally.

For direct fire, the altitude function $A$ and the inclination function $I$ are used to determine the required angle of elevation ($\phi$) and the angle of descent ($\beta$). For small angles, these are expressed as:
*   $\sin 2\phi = 2C [I(V) - \Delta A / \Delta S]$
*   $\sin 2\beta = 2C [\Delta A / \Delta S - I(v)]$

## Sources
Compiled from: britannica11 vol02b baconthorpe to bankruptcy
---
*Written by the AI Librarian strictly from the public-domain books of the archive. Topic memory: data/written-topics.json*
