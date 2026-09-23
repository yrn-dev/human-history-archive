# Ballistic Angles and Trajectory Calculations

In the study of ballistics, specifically regarding the firing of guns, several distinct angles are used to determine the trajectory of a shot and its eventual impact. These calculations involve the relationship between the initial velocity of the projectile, the range, and the physical elevation of the firing position.

## Elevation and Descent Angles
The angle of elevation, denoted as $\phi$, is the tangent elevation (T.E.). When calculating the quadrant elevation (Q.E.), the formula is $\phi - S$, where $S$ represents the angular depression of the line of sight $OB$. If the firing point $O$ is $h$ feet vertically above the target $B$, the angle $S$ at a range of $R$ yards is determined by the formula $\sin S = h/3R$. For small angles expressed in minutes (taking the radian as 3438'), this is expressed as $S = 1146h/R$.

The angle of descent, denoted as $\beta$, represents the angle at which the shot strikes a horizontal plane, such as water. To obtain this angle, the value of $\beta$ must be increased by $S$. In cases of direct fire, where pseudo-velocities $U$ and $u$ and real velocities $V$ and $v$ are undistinguishable, the angle of elevation and descent can be calculated using the following formulas for small angles:
*   $\sin 2\phi = 2C [I(V) - \Delta A/\Delta S]$
*   $\sin 2\beta = 2C [\Delta A/\Delta S - I(v)]$

## Trajectory and Range Tables
The compilation of range tables involves calculating the remaining velocity $v$, the time of flight $t$, the angle of elevation $\phi$, and the descent $\beta$. For example, a 6-in. gun with a muzzle velocity $V = 2150$ f/s and a coefficient of reduction $n = 0.96$ can be calculated for ranges of 500, 1000, 1500, and 2000 yards. Discrepancies between calculated and tabulated results can indicate the influence of the muzzle velocity $V$ or a slight change in the coefficient of reduction $n$.

To simplify these calculations and avoid the intermediate step of calculating remaining velocity $v$, Captain Braccialini Scipione devised a double-entry table (later adapted by A. G. Hadcock). This table uses the formula $\sin 2\phi = Ca$, where $a$ is a function of the initial velocity $V$ and the reduced range $R/C$.

## Factors Influencing Flight
Several variables affect the path of a projectile:

**Slope and Sight:** When firing up or down a slope, the alteration of the tangent elevation is almost insensible; however, the quadrant elevation requires the addition or subtraction of the angle of sight.

**Drift:** A shot fired from a rifled gun does not move in a vertical plane. Instead, the mean plane of the trajectory is inclined to the true vertical at a small angle (typically 2 or 3 degrees). This phenomenon, known as drift, is a gyroscopic effect. It is increased by the rotation of the shot and is reversed in direction if the rifling twist is changed from right to left-handed. To compensate for this, the back sight is tilted to the vertical at an angle $\delta$, known as the permanent angle of deflection.

**Velocity and Time:** Given a ballistic coefficient $C$, initial velocity $V$, and range $R$ (or $X = 3R$ ft.), the final velocity $v$ is calculated as $S(v) = S(V) - X/C$. The time of flight $T$ is then found via $T = C\{T(V) - T(v)\}$. The total deviation in the range $OB$ is $\delta = \phi + \beta = C\{D(V) - D(v)\}$.

## Computational Methods
Different mathematical approaches have been used to calculate trajectories:
*   **Siacci's Method:** Lieutenant A. H. Wolley-Dod employed this method using about twenty arcs to calculate trajectories. Siacci's altitude-function is particularly useful in direct fire for immediately providing the angle of descent $\beta$ and the required angle of elevation $\phi$ for a given range.
*   **Tenuity-Factor Method:** Captain Ingalls obtained accurate results by assuming a mean tenuity-factor $\tau = 0.68$ (corresponding to a height of about 2 m), working in two arcs over the trajectory—up to the vertex and then down.

## Sources
Compiled from: britannica11 vol02b baconthorpe to bankruptcy
---
*Written by the AI Librarian strictly from the public-domain books of the archive. Topic memory: data/written-topics.json*
