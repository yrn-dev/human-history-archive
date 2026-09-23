# [eta] = 1/2([phi] + [theta])

In the context of ballistic calculations, specifically the application of Siacci's method for determining trajectories in high angle fire, the formula $\eta = 1/2(\phi + \theta)$ serves as a mathematical approximation for the variable $\eta$. This formula represents the arithmetic mean of the angles $\phi$ and $\theta$.

## Application in Siacci's Method
When calculating a trajectory in high angle fire through the use of successive arcs of small curvature, the process begins at the start of an arc with a velocity $v_\phi$ at an angle $\phi$. Once the curvature of the arc $\phi - \theta$ is determined, the expression $\eta = 1/2(\phi + \theta)$ is utilized as a "good first approximation" for $\eta$.

This approximation is employed to calculate the pseudo-velocity $u_\phi$ using the formula:
$u_\phi = v_\phi \cos \phi \sec \eta$

Subsequently, using the given values of $\phi$ and $\theta$, the value $u_\theta$ is calculated via one of two formulae:
1. $I(u_\theta) = I(u_\phi) - \frac{\tan \phi - \tan \theta}{C \sec \eta}$
2. $D(u_\theta) = D(u_\phi) - \frac{\phi\text{deg} - \theta\text{deg}}{C \cos \eta}$

## Role of $\eta$ in Trajectory Equations
The variable $\eta$ appears in several equations used to determine the characteristics of the arc $\phi - \theta$:
*   **Time of flight:** $\phi t_\theta = C[T(u_\phi) - T(u_\theta)]$
*   **Horizontal distance:** $\phi x_\theta = C \cos \eta [S(u_\phi) - S(u_\theta)]$
*   **Ratio of coordinates:** $\phi(y/x)_\theta = \tan \phi - C \sec \eta [I(u_\phi) - \Delta A/\Delta S]$, where $\Delta$ denotes a finite tabular difference of the function between the final and initial pseudo-velocity.

The velocity at the end of the arc, $v_\theta$, is further defined as $v_\theta = u_\theta \sec \theta \cos \eta$. For subsequent arcs, this final velocity $v_\theta$ and angle $\theta$ are treated as the initial velocity $v_\phi$ and angle $\phi$.

## Geometric Significance and Accuracy
In Niven's method of calculating trajectories, $\eta$ is defined as the inclination of the chord of the arc of the trajectory. However, Niven's method requires $\eta$ to be known with high accuracy, as a 1% variation in $\eta$ results in more than a 1% variation in $\tan \eta$.

To avoid this difficulty, Siacci's altitude-function $A$ or $A(u)$ is used. This allows $y/x$ to be calculated without the introduction of $\sin \eta$ or $\tan \eta$. In this system, $\eta$ only appears in the forms $\cos \eta$ or $\sec \eta$. Because these functions vary very slowly for moderate values of $\eta$, the value does not need to be calculated with great regard for accuracy. Consequently, the arithmetic mean $1/2(\phi + \theta)$ is considered sufficient for $\eta$ over any arc $\phi - \theta$ of moderate extent.

## High Angle Fire Considerations
In long range high angle fire, the shot reaches heights where the tenuity of the air requires correction. To manage this, the curvature $\phi - \theta$ of an arc is chosen so that the height ascended ($\phi y_\theta$) is limited to approximately 1000 ft. This height is equivalent to a 3% diminution in the tenuity factor $\tau$ or a fall of 1 inch in the barometer.

Additionally, Captain James M. Ingalls, U.S.A., provided a rule for approximating high angle trajectories in a single arc. This rule assumes the mean density of the air is the density at two-thirds of the estimated height of the vertex, based on the fact that in an unresisted parabolic trajectory (such as a stream of bullets from a Maxim gun or a jet of water), the average height of the shot is two-thirds the height of the vertex.

## Sources
Compiled from: britannica11 vol02b baconthorpe to bankruptcy
---
*Written by the AI Librarian strictly from the public-domain books of the archive. Topic memory: data/written-topics.json*
