# Treating Final Velocity $v_{[\theta]}$ and Angle $[\theta]$ as Initial

In the calculation of trajectories for high angle fire, specifically when applying Siacci's method, the path of a shot is determined through the use of successive arcs of small curvature. This process involves calculating the state of the projectile at the end of one arc and using those values to begin the next.

## Calculation of Successive Arcs
The process begins at the start of an arc with an initial velocity $v_{[\phi]}$ and an angle $[\phi]$. To determine the trajectory, the curvature of the arc $[\phi] - [\theta]$ is first established. A good first approximation for the mean angle $[\eta]$ is given by the formula $[\eta] = 1/2([\phi] + [\theta])$.

From this, a pseudo-velocity $u_{[\phi]}$ is calculated using the formula:
$u_{[\phi]} = v_{[\phi]} \cos [\phi] \sec [\eta]$

Using the values for $[\phi]$ and $[\theta]$, the pseudo-velocity at the end of the arc, $u_{[\theta]}$, is then calculated using one of two formulae:
1. $I(u_{[\theta]}) = I(u_{[\phi]}) - \frac{\tan [\phi] - \tan [\theta]}{C \sec [\eta]}$
2. $D(u_{[\theta]}) = D(u_{[\phi]}) - \frac{[\phi]_{\text{deg}} - [\theta]_{\text{deg}}}{C \cos [\eta]}$

## Final Velocity and Transition
The velocity at the end of the arc, denoted as $v_{[\theta]}$, is determined by the equation:
$v_{[\theta]} = u_{[\theta]} \sec [\theta] \cos [\eta]$

To continue the trajectory calculation, this final velocity $v_{[\theta]}$ and the final angle $[\theta]$ are treated as the initial velocity $v_{[\phi]}$ and initial angle $[\phi]$ for the subsequent arc. The calculation then proceeds as before.

## High Angle Fire and Air Tenuity
In long range high angle fire, the shot reaches heights where corrections for the tenuity of the air become important. Consequently, the curvature $[\phi] - [\theta]$ of an arc is chosen such that the height ascended, denoted as $[\phi]y_{[\theta]}$, is limited to approximately 1000 ft. This height is equivalent to a 3% diminution in the tenuity factor $[\tau]$, or a fall of 1 inch in the barometer.

## Approximating Trajectories
Captain James M. Ingalls, U.S.A., provided a rule for approximating a high angle trajectory within a single arc. This rule assumes that the mean density of the air can be taken as the density at two-thirds of the estimated height of the vertex. This is based on the fact that in a stream of bullets from a Maxim gun, or in a jet of water (unresisted parabolic trajectories), the average height of the shot is two-thirds the height of the vertex.

## Recorded Range Example
The archive records a specific instance from 1888 involving a 9.2-in. gun. A shot weighing 380 lb was fired with an elevation of $40^{\circ}$ and a velocity of 2375 f/s. The resulting range was approximately 12 m., with a flight time of about 64 sec.

## Sources
Compiled from: britannica11 vol02b baconthorpe to bankruptcy
---
*Written by the AI Librarian strictly from the public-domain books of the archive. Topic memory: data/written-topics.json*
