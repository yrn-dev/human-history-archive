# T(v) = [Sum]([Delta]v)/gp + a constant

In the field of ballistics, the function $T(v)$ is used to determine the time required for the velocity of a projectile to decrease. This calculation is based on a standard shot for which the ballistic coefficient $C=1$, and for which a corresponding ballistic table is calculated.

## Calculation of Time and Velocity
The time in seconds for the velocity of a standard shot to drop by a value of $\Delta v$ is denoted as $\Delta T$. To determine this value, $p$ is determined experimentally and tabulated as a function of velocity ($v$). By taking $\Delta v = 10$, the average value of $p$ within that interval is used to find $\Delta T$.

The value of $T$ at any given velocity $v$, denoted as $T(v)$, is the sum of all preceding values of $\Delta T$ plus an arbitrary constant. This relationship is expressed mathematically as:
$T(v) = \sum (\Delta v)/gp + \text{a constant}$, or $\int dv/gp + \text{a constant}$

In these equations, $p$ is known as a function of $v$. Because the use of the table typically requires only the difference between two tabular values—specifically for an initial velocity $V$ and a final velocity $v$—the arbitrary constant does not affect the result. The difference is expressed as:
$T(V) - T(v) = \sum_{v:V} \Delta v/gp$ or $\int_{v:V} dv/gp$

For a shot with a specific ballistic coefficient $C$, the time $t$ is calculated as:
$t = C[T(V) - T(v)]$

To simplify calculations and avoid proportional parts, values for $T(v)$ for unit increments of $v$ are interpolated in an extended ballistic table.

## Advance and Distance
The distance a shot advances is denoted as $\Delta s$. If a shot advances $\Delta s$ feet in time $\Delta t$, while the velocity falls from $v + 1/2\Delta v$ to $v - 1/2\Delta v$, the loss of kinetic energy in foot-pounds is $R\Delta s = wv\Delta v/g$. This leads to the formula:
$\Delta s = wv\Delta v/nd^2pg = C\Delta S$

Here, $\Delta S$ represents the advance in feet of a shot where $C=1$ while the velocity falls by $\Delta v$ through the average velocity $v$. The formula for $\Delta S$ is:
$\Delta S = v\Delta v/gp = v\Delta T$

The sum of all values of $\Delta S$ up to an assigned velocity $v$ is denoted as $S(v)$, where:
$S(v) = \sum (\Delta S) + \text{a constant}$

Between two assigned velocities $V$ and $v$, the difference is:
$S(V) - S(v) = \sum_{v:V} \Delta T = \sum v\Delta v/gp$ or $\int_{v:V} vdv/gp$

For a shot with ballistic coefficient $C$, the advance $s$ in feet is:
$s = C[S(V) - S(v)]$

## Direction of Motion and the Degree Table
A "degree table," attributed to Sir W. D. Niven, F.R.S., is used to determine the change in the direction of motion of a shot flying nearly horizontally as velocity changes from $V$ to $v$. 

If the tangent at the point of trajectory where velocity is $v$ makes an angle $i$ radians with the horizon, and air resistance acts tangentially, the relationship is $v(di/dt) = g \cos i$. In direct fire problems where the trajectory is flat enough that $\cos i$ is indistinguishable from unity, the equation becomes $v(di/dt) = g$, or $di/dt = g/v$. Consequently, $\Delta i/\Delta t = g/v$.

If the change in inclination in degrees is denoted by $\delta$ or $\Delta \delta$, the relationship to radians is $\delta/180 = i/\pi$. For a standard projectile, the change in direction is expressed as:
$\Delta I = g\Delta T/v = \Delta v/vp$
$\Delta D = 180g/\pi \Delta T/v$

The total change in direction is calculated as:
$I(V) - I(v) = \sum_{v:V} \Delta v/vp$ or $\int_{v:V} dv/vp$
$D(V) - D(v) = 180/\pi [I(V) - I(v)]$

## Ballistic Table Functions
The values $T, S, D, I,$ and $A$ (where $A$ is the altitude function used for high angle fire) are presented numerically in abridged ballistic tables. In these tables, velocity serves as the argument, typically proceeding by increments of 10 f/s. The column for $p$ is derived from experimental data, while the other columns are calculated based on the aforementioned formulas.

## Sources
Compiled from: britannica11 vol02b baconthorpe to bankruptcy
---
*Written by the AI Librarian strictly from the public-domain books of the archive. Topic memory: data/written-topics.json*
