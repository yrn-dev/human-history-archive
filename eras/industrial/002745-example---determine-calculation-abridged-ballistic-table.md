# Example 3: Calculation with the Abridged Ballistic Table

In the study of exterior ballistics—the science of projectile motion after the initial impulse—the abridged ballistic table is used to determine the trajectory and performance of a projectile. Example 3 specifically demonstrates how to calculate the remaining velocity, time of flight, angle of elevation, and angle of descent for a 6-inch gun.

## Parameters of Example 3
The calculation for this specific example utilizes a 6-inch gun with the following established values:
*   **Muzzle Velocity (V):** 2150 f/s
*   **Coefficient of Reduction (n):** 0.96
*   **Ranges for Calculation:** 500, 1000, 1500, and 2000 yards

The objective of the exercise is to determine the remaining velocity ($v$), the time of flight ($t$), the angle of elevation ($\phi$), and the angle of descent ($\beta$) at each of these specified ranges.

## Theoretical Framework for Calculation
The calculations are based on the principles of direct fire, which is officially defined as fire from guns using a full charge at an elevation not exceeding 15 degrees. In these instances, the vertical component of air resistance is considered insensible, meaning the actual velocity and its horizontal component (or the component parallel to the line of sight) are treated as undistinguishable.

To find the required values, the following process is employed:
1.  **Final Velocity ($v$):** Given the ballistic coefficient $C$, initial velocity $V$, and a range of $R$ yards (where $X = 3R$ feet), the final velocity is calculated using the formula $S(v) = S(V) - X/C$.
2.  **Time of Flight ($T$):** This is determined by the formula $T = C\{T(V) - T(v)\}$.
3.  **Total Deviation ($\delta$):** The total deviation in the range, which is the sum of the angle of departure ($\phi$) and descent ($\beta$), is calculated as $\delta = \phi + \beta = C\{D(V) - D(v)\}$.
4.  **Angles of Elevation and Descent:** To divide the total deviation between $\phi$ and $\beta$, the vertex of the trajectory (point A) is used as the point of half-time. The velocity at the vertex ($v_0$) is found via $T(v_0) = 1/2\{T(V) + T(v)\}$. From there:
    *   The angle of elevation is $\phi = C\{D(V) - D(v_0)\}$.
    *   The angle of descent is $\beta = C\{D(v_0) - D(v)\}$.

## The Abridged Ballistic Table and Integration
The abridged ballistic table provides numerical values for functions such as $T, S, D, I,$ and $A$, using velocity as the argument in increments of 10 f/s. In regions where the value $p$ can be represented by an empirical formula of a single power of $v$ (expressed as $v^m$), integration replaces summation to determine the values.

The table includes an index $m$ and a corresponding value of $gp$ (denoted as $f(v)$, $v^m/k$, or $Cr$, where $r$ is retardation). For example, at a velocity of 1800, $m$ is 2 and $\log k$ is 3.8807404; at 1370, $m$ is 3 and $\log k$ is 7.0190977. These figures were converted from kilogramme-metre to pound-foot units by Colonel Ingalls for use in extended ballistic tables.

## Adjustments for Elevation and Slope
The value of $\phi$ represents the tangent elevation (T.E.). However, the quadrant elevation (Q.E.) is calculated as $\phi - S$, where $S$ is the angular depression of the line of sight. If the point of origin $O$ is $h$ feet vertically above point $B$, the angle $S$ at a range of $R$ yards is given by $\sin S = h/3R$. For small angles expressed in minutes, this is calculated as $S = 1146h/R$.

When firing up or down a slope, the alteration of the tangent elevation is almost insensible, but the quadrant elevation must be adjusted by adding or subtracting the angle of sight. Additionally, to find the angle at which a shot strikes a horizontal plane (such as water), the angle $\beta$ must be increased by $S$.

## Sources
Compiled from: britannica11 vol02b baconthorpe to bankruptcy
---
*Written by the AI Librarian strictly from the public-domain books of the archive. Topic memory: data/written-topics.json*
