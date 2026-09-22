# Ballistic Tables and the Representation of Velocity

The construction of ballistic tables relies on the experimental measurement of the resistance of air and the subsequent mathematical representation of a projectile's velocity and retardation. These tables allow for the calculation of the time and distance a shot travels as its velocity decreases.

## Foundations of Air Resistance
The basis for current knowledge regarding air resistance is derived from experiments conducted by the Rev. F. Bashforth between 1864 and 1880. Bashforth determined that no simple algebraical law could represent air resistance across a wide range of velocity. To gather data, he utilized a chronograph and equidistant electric screens with vertical threads or wire to measure the time at which a shot, flying nearly horizontally, cut through the screens. Using the calculus of finite differences, these records were used to infer the retardation and velocity of the shot, and consequently, the resistance of the air.

While Bashforth used old-fashioned projectiles fired from muzzle-loading guns, modern designs can still utilize these results by determining a well-chosen value of $n$ through a few experiments. For a modern rifle bullet, a value of $n = 0.8$ or less is considered a good average.

## The Ballistic Coefficient and Time Calculations
To construct a ballistic table, experimental values of $p$ are used for a standard projectile fired under standard conditions in air of standard density. The process involves determining the time $t$ (in seconds) required for a shot of diameter $d$ (inches) and weight $w$ (lb) to fall from an initial velocity $V$ to a final velocity $v$. In these calculations, the shot is assumed to move horizontally, and the curving effect of gravity is ignored.

The resistance of the air, $R$ (lb), causes a drop in velocity $\Delta v$ over a time $\Delta t$. The loss of momentum is expressed as $w\Delta v/g$, leading to the formula $\Delta t = w\Delta v/nd^2pg$. The term $w/nd^2$ is defined as $C$, known as the ballistic coefficient or the driving power of the shot. This allows the time to be expressed as $\Delta t = C\Delta T$, where $\Delta T = \Delta v/gp$.

The total time $T(v)$ at any velocity $v$ is the sum of all preceding values of $\Delta T$ plus an arbitrary constant. For a shot with a ballistic coefficient $C$, the time is calculated as $t = C[T(V) - T(v)]$.

## Distance and Direction of Motion
The advance of a shot in feet is denoted by $s$. For a shot where $C=1$, the advance is $\Delta S$, where $\Delta S = v\Delta v/gp$ or $v\Delta T$. The total advance $S(v)$ is the sum of all $\Delta S$ values up to a specific velocity. For a shot with ballistic coefficient $C$, the distance is $s = C[S(V) - S(v)]$.

Additionally, a "degree table" developed by Sir W. D. Niven determines the change in the direction of motion. If the tangent of the trajectory makes an angle $i$ (radians) with the horizon, and air resistance acts tangentially, the relationship is $v(di/dt) = g \cos i$. In direct fire problems where the trajectory is flat enough that $\cos i$ is nearly unity, this simplifies to $di/dt = g/v$, or $\Delta i/\Delta t = g/v$.

## Velocity Representation and Integration
In specific regions of velocity where $p$ can be represented with sufficient accuracy by an empirical formula consisting of a single power of $v$ (expressed as $v^m$), the summation used in ballistic calculations can be replaced by integration. Colonel Zabudski analyzed Krupp experiments to find the most appropriate index $m$ for various velocity regions. The corresponding value of $gp$ is denoted as $f(v)$, $v^m/k$, or $Cr$, where $r$ represents the retardation.

## Pressure and Energy Curves
The relationship between volume and pressure of powder-gas in a gun can be represented by an indicator diagram. The net work realized by the powder-gas as the shot advances is equated to the kinetic energy $e$ of the shot.

Different pressure-curve assumptions result in different velocity-curve shapes:
* **Uniform Pressure:** If pressure is uniform (as in a Zalinski pneumatic dynamite gun), the pressure-curve is a straight line, the energy-curve is a straight line, and the velocity-curve is a parabola.
* **Uniformly Falling Pressure:** If the pressure-curve is a straight line sloping downwards, the energy-curve is a downward-curving parabola, the velocity-curve is an ellipse or circle, and the time-curve is a sinusoid.
* **Uniformly Rising Pressure:** If the pressure-curve is a straight line sloping upwards, the energy-curve is an upward-curving parabola and the velocity-curve is a hyperbola.

In cases where no observable law exists, the area of the pressure-curve is calculated using Simpson's rule or read via a planimeter.

## Sources
Compiled from: britannica11 vol02b baconthorpe to bankruptcy
---
*Written by the AI Librarian strictly from the public-domain books of the archive. Topic memory: data/written-topics.json*
