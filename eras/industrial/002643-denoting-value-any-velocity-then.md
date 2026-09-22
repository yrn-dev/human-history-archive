# Ballistic Tables and the Calculation of T(v)

In the study of ballistics, the determination of a projectile's flight involves calculating the time and distance of travel as velocity decreases due to air resistance. A central component of this process is the construction of ballistic tables, which use experimental data to determine the behavior of a shot.

## Air Resistance and the Ballistic Coefficient
Experimental results indicate that the resistance of similar shots at the same velocity is proportional to the cross section or the square of the diameter ($d^2$). Resistance ($R$) is expressed as $R = d^2p$, where $p$ represents the resistance in pounds for a similar 1-inch projectile at the same velocity. These values of $p$ are typically based on a standard air density of 534.22 grains per cubic foot (dry air at sea-level in Greenwich at 62°F and a barometric height of 30 in). To account for the humidity of the English climate, a standard temperature of 60°F is often used to maintain the same density, as aqueous vapour reduces air density.

If the standard density changes, a coefficient of tenuity ($\tau$) is applied, making the resistance $R = \tau d^2p$. Further calculations utilize the ballistic coefficient ($C$), also known as driving power, defined by the formula $C = w/nd^2$, where $w$ is the weight of the shot in pounds and $n$ is a value determined by experiment (for example, $n = 0.8$ is often used for modern rifle bullets).

## The Time Function T(v)
The function $T(v)$ denotes the value of time at any given velocity $v$. To determine this, the time $\Delta T$ is first calculated, which represents the seconds required for the velocity of a standard shot (where $C=1$) to drop by an increment $\Delta v$. Using an average value of $p$ in an interval (typically where $\Delta v = 10$), $\Delta T$ is defined as $\Delta v/gp$.

The value of $T(v)$ is the sum of all preceding values of $\Delta T$ plus an arbitrary constant. This is expressed mathematically as:
$T(v) = \sum(\Delta v)/gp + \text{constant}$ or $\int dv/gp + \text{constant}$.

Because the ballistic table is used to find the difference between an initial velocity $V$ and a final velocity $v$, the arbitrary constant is omitted in practical application:
$T(V) - T(v) = \sum_{v:V} \Delta v/gp$ or $\int_{v:V} dv/gp$.

For a specific shot with a ballistic coefficient $C$, the actual time $t$ is calculated as $t = C[T(V) - T(v)]$.

## Related Ballistic Functions
The ballistic table includes other functions alongside $T$, using velocity as the argument:

*   **The Distance Function S(v):** This represents the sum of all values of $\Delta S$ (the advance in feet of a shot where $C=1$) up to a velocity $v$. It is calculated as $S(v) = \sum(\Delta S) + \text{constant}$. The advance $s$ for a shot with ballistic coefficient $C$ is $s = C[S(V) - S(v)]$.
*   **The Degree and Inclination Functions (D and I):** These determine the change in the direction of motion. For a shot flying nearly horizontally, the infinitesimal decrement of the angle $i$ (radians) is given by $v(di/dt) = g \cos i$. In direct fire, where $\cos i$ is approximately unity, this becomes $di/dt = g/v$. The function $I(V) - I(v)$ is the sum of $\Delta v/vp$ or the integral $\int_{v:V} dv/vp$. The degree table $D(v)$ converts this to degrees: $D(V) - D(v) = 180/\pi [I(V) - I(v)]$.

## Application in Trajectory Calculation
In practical gunnery, these functions allow for the calculation of flight characteristics. Given a ballistic coefficient $C$, initial velocity $V$, and range $X$ (in feet), the final velocity $v$ is found via $S(v) = S(V) - X/C$, and the time of flight is $T = C\{T(V) - T(v)\}$.

For high-angle fire, Siacci's method may be used to calculate trajectories through successive arcs of small curvature. This involves calculating "pseudo-velocity" ($u$) and utilizing the functions $T, S, I,$ and $A$ (the altitude function). For an arc between angles $\phi$ and $\theta$, the time is denoted as $\phi t_\theta = C[T(u_\phi) - T(u_\theta)]$.

## Sources
Compiled from: britannica11 vol02b baconthorpe to bankruptcy
---
*Written by the AI Librarian strictly from the public-domain books of the archive. Topic memory: data/written-topics.json*
