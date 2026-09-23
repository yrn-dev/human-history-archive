# Calculation of Pseudo-Velocity $u_\phi$

In the study of ballistics and the calculation of trajectories, particularly when employing Siacci's method, the concept of pseudo-velocity is used to simplify the integration of equations of motion. This method is especially applicable to high angle fire, where the trajectory is calculated through a series of successive arcs of small curvature.

## Definition and Concept of Pseudo-Velocity
Pseudo-velocity, denoted as $u$, is defined as $u = q \sec \eta$. In this context, $u$ serves as a quasi-component that runs parallel to the mean direction of the tangent, such as the direction of the chord of the arc. The value $\eta$ represents the mean value of the angle $i$, as well as $\cos i$ and $\sec i$, which vary slowly in ordinary trajectories. 

When a trajectory is divided into arcs of small curvature—defined as the angle between the tangents or normals at the ends of the arc—the arithmetic mean of the initial angle $\phi$ and the final angle $\theta$ provides a sufficient approximation for $\eta$:
$$\eta = \frac{1}{2}(\phi + \theta)$$

## Calculating $u_\phi$ in High Angle Fire
When calculating a trajectory in high angle fire by successive arcs, the process begins at the start of an arc with an initial angle $\phi$ and an initial velocity $v_\phi$. To determine the pseudo-velocity at the beginning of this arc, denoted as $u_\phi$, the following formula is used:
$$u_\phi = v_\phi \cos \phi \sec \eta$$

Once $u_\phi$ is established, it is used to calculate the pseudo-velocity at the end of the arc, $u_\theta$, using the given values of $\phi$ and $\theta$ through either of two formulae:
1. $I(u_\theta) = I(u_\phi) - \frac{\tan \phi - \tan \theta}{C \sec \eta}$
2. $D(u_\theta) = D(u_\phi) - \frac{\phi^\text{deg} - \theta^\text{deg}}{C \cos \eta}$

## Application to Trajectory Arcs
The pseudo-velocities are essential for determining the physical characteristics of the arc between the initial point $\phi$ and the final point $\theta$:
*   **Time of flight:** $\phi t_\theta = C[T(u_\phi) - T(u_\theta)]$
*   **Horizontal distance:** $\phi x_\theta = C \cos \eta [S(u_\phi) - S(u_\theta)]$
*   **Altitude ratio:** $\phi(y/x)_\theta = \tan \phi - C \sec \eta [I(u_\phi) - \Delta A/\Delta S]$, where $\Delta$ represents any finite tabular difference of the function between the initial and final pseudo-velocity.

The final velocity at the end of the arc, $v_\theta$, is then derived from the final pseudo-velocity $u_\theta$ using the formula:
$$v_\theta = u_\theta \sec \theta \cos \eta$$
This final velocity $v_\theta$ and the angle $\theta$ then serve as the initial velocity $v_\phi$ and angle $\phi$ for the subsequent arc.

## Direct Fire Simplifications
In instances of direct fire, the distinction between pseudo-velocities ($U$ and $u$) and real velocities ($V$ and $v$) becomes undistinguishable. In these cases, $\sec \eta$ may be replaced by unity. Consequently, if $y = 0$, the formula for the angle of elevation $\phi$ simplifies to:
$$\tan \phi = C [I(V) - \Delta A/\Delta S]$$

## Sources
Compiled from: britannica11 vol02b baconthorpe to bankruptcy
---
*Written by the AI Librarian strictly from the public-domain books of the archive. Topic memory: data/written-topics.json*
