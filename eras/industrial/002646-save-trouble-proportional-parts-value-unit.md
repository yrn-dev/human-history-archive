# Calculation of T(v) for Unit Increment of Velocity

In the study of ballistics, the determination of the time it takes for a projectile's velocity to decrease is a central calculation. The value $T(v)$ represents the time at any given velocity $v$. To determine this value, the time in seconds ($\Delta T$) is measured for the velocity to drop by a specific amount ($\Delta v$) for a standard shot where the ballistic coefficient $C=1$.

## Determination of T(v)
The calculation of $T(v)$ relies on the value of $p$, which is determined experimentally and tabulated as a function of velocity. Velocity serves as the argument for the ballistic table. By taking $\Delta v = 10$, the average value of $p$ within that interval is used to find $\Delta T$.

The value of $T(v)$ is expressed as the sum of all preceding values of $\Delta T$ plus an arbitrary constant. This is represented mathematically as:
$T(v) = \sum (\Delta v)/gp + \text{a constant}$, or $\int dv/gp + \text{a constant}$.

Because the constant can be any arbitrary number, it is not required for practical application; the user only needs the difference between two tabular values for an initial velocity $V$ and a final velocity $v$. This difference is expressed as:
$T(V) - T(v) = \sum_{v:V} \Delta v/gp$ or $\int_{v:V} dv/gp$.

For a shot with a specific ballistic coefficient $C$, the time $t$ is calculated as:
$t = C[T(V) - T(v)]$.

## Unit Increment and Interpolation
To avoid the difficulties associated with proportional parts, the value of $T(v)$ for a unit increment of $v$ is interpolated. This process is carried out using a full-length extended ballistic table for $T$.

## Relation to Distance and Kinetic Energy
The relationship between velocity, time, and distance is further defined by the loss of kinetic energy. If a shot advances a distance $\Delta s$ (in feet) during a time $\Delta t$, and the velocity falls from $v + 1/2\Delta v$ to $v - 1/2\Delta v$, the loss of kinetic energy in foot-pounds is:
$R\Delta s = w(v + 1/2\Delta v)^2/g - w(v - 1/2\Delta v)^2/g = wv\Delta v/g$.

Consequently, the distance $\Delta s$ is determined as:
$\Delta s = wv\Delta v/nd^2pg = C\Delta S$.

In this context, $\Delta S$ is defined as:
$\Delta S = v\Delta v/gp = v\Delta T$.

## Sources
Compiled from: britannica11 vol02b baconthorpe to bankruptcy
---
*Written by the AI Librarian strictly from the public-domain books of the archive. Topic memory: data/written-topics.json*
