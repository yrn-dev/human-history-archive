# Calculation of Trajectory Velocity and Arcs

In the study of ballistics, specifically regarding the calculation of trajectories in high angle fire, the method developed by Siacci is employed to determine the path of a projectile through successive arcs of small curvature. This process involves the use of pseudo-velocities and specific trigonometric approximations to manage the complexities of air resistance and atmospheric density.

## Siacci's Method and Pseudo-Velocity
The calculation of a trajectory is often intractable when using simple mathematical assumptions for the function $f(v)$, such as the quadratic or cubic laws ($f(v) = v^2/k$ or $v^3/k$). To resolve this, the method utilizes the observation that in ordinary practice, quantities such as $i$, $\cos i$, and $\sec i$ vary slowly. These are replaced by their mean values, denoted as $[\eta]$, $\cos [\eta]$, and $\sec [\eta]$.

Siacci introduced the "pseudo-velocity" $u$, defined by the formula $u = q \sec [\eta]$. This value represents a quasi-component parallel to the mean direction of the tangent, such as the direction of the chord of the arc. The curvature of an arc is defined as the angle between the tangents or normals at the ends of the arc.

## Calculation of Arc Velocity
When calculating a trajectory by successive arcs of small curvature, the process begins at the start of an arc with an angle $[\phi]$ and a velocity $v_{[\phi]}$. A first approximation for the mean value $[\eta]$ is determined by the formula $[\eta] = 1/2([\phi] + [\theta])$.

The initial pseudo-velocity $u_{[\phi]}$ is calculated as:
$u_{[\phi]} = v_{[\phi]} \cos [\phi] \sec [\eta]$

From the given values of $[\phi]$ and $[\theta]$, the final pseudo-velocity $u_{[\theta]}$ is then calculated using one of two formulae:
1. $I(u_{[\theta]}) = I(u_{[\phi]}) - \frac{\tan [\phi] - \tan [\theta]}{C \sec [\eta]}$
2. $D(u_{[\theta]}) = D(u_{[\phi]}) - \frac{[\phi]\text{deg} - [\theta]\text{deg}}{C \cos [\eta]}$

The real velocity $v_{[\theta]}$ at the end of the arc is then given by the formula:
$v_{[\theta]} = u_{[\theta]} \sec [\theta] \cos [\eta]$

To continue the calculation for the next arc, this final velocity $v_{[\theta]}$ and angle $[\theta]$ are treated as the initial velocity $v_{[\phi]}$ and angle $[\phi]$.

## High Angle Fire and Atmospheric Factors
In long range high angle fire, the projectile reaches heights where the tenuity of the air requires correction. To maintain accuracy, the curvature $[\phi] - [\theta]$ of an arc is chosen so that the height ascended, denoted as $_{\phi}y_{\theta}$, is limited to approximately 1000 ft. This limit is equivalent to a 3% diminution in the tenuity factor $[\tau]$ or a fall of 1 inch in the barometer.

Captain James M. Ingalls, U.S.A., provided a rule for approximating high angle trajectories in a single arc. This rule assumes the mean density of the air is the density at two-thirds of the estimated height of the vertex. This is based on the fact that in an unresisted parabolic trajectory—such as a stream of bullets from a Maxim gun or a jet of water—the average height of the shot is two-thirds the height of the vertex.

## Direct Fire and Range Records
In cases of direct fire, the pseudo-velocities $U$ and $u$ and the real velocities $V$ and $v$ are undistinguishable. In these instances, $\sec [\eta]$ may be replaced by unity. Siacci's altitude-function is used in direct fire to immediately determine the angle of descent $[\beta]$ and the angle of elevation $[\phi]$ required for a specific range.

The archive records a significant ballistic achievement from 1888 involving a 9.2-in. gun. A shot weighing 380 lb was fired with a velocity of 2375 f/s at an elevation of $40^\circ$. The resulting range was approximately 12 m., with a flight time of about 64 seconds.

## Sources
Compiled from: britannica11 vol02b baconthorpe to bankruptcy
---
*Written by the AI Librarian strictly from the public-domain books of the archive. Topic memory: data/written-topics.json*
