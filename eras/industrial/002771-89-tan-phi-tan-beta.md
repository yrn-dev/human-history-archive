# tan [phi] - tan [beta] = C [I(V) - L(v)]

The expression $\tan [\phi] - \tan [\beta] = C [I(V) - L(v)]$ is a formula utilized within the study of ballistics, specifically in the application of Siacci's method for calculating trajectories. This formula relates the angle of elevation and the angle of descent to velocity functions.

## Application in Direct Fire
In the context of direct fire, the formula is used to determine the angle of elevation $[\phi]$ required for a specific range (measured in yards $R$ or feet $X$) between the velocity limits $V$ and $v$. It also provides the angle of descent $[\beta]$. 

Under conditions of direct fire, certain variables become indistinguishable or simplified:
* The real velocities $V$ and $v$ are undistinguishable from the pseudo-velocities $U$ and $u$.
* The term $\sec [\eta]$ may be replaced by unity.

When these conditions are met and $y = 0$, the relationship can be expressed as $\tan [\phi] = C [I(V) - \Delta A/\Delta S]$. Consequently, the relationship between the angle of elevation and the angle of descent is defined by the equation $\tan [\phi] - \tan [\beta] = C [I(V) - L(v)]$. This further allows for the calculation of the angle of descent as $\tan [\beta] = C [\Delta A/\Delta S - I(v)]$.

## Small Angle Approximations
For calculations involving small angles, the aforementioned formulas can be rewritten. The angle of elevation is represented by $\sin 2[\phi] = 2C [I(V) - \Delta A/\Delta S]$, and the angle of descent is represented by $\sin 2[\beta] = 2C [\Delta A/\Delta S - I(v)]$.

## Siacci's Method and Trajectory Calculation
The formula exists within a broader system of ballistic calculations developed by Siacci and slightly modified by General Mayevski. This system employs a ballistic table for direct fire that defines several functions: $T$, $S$, $I$, and $D$.

In these calculations, $\eta$ represents the inclination of the chord of the arc of the trajectory. To avoid the difficulties associated with the accuracy of $\tan [\eta]$, Siacci's altitude-function $A$ or $A(u)$ is used. This allows $y/x$ to be calculated using $\cos [\eta]$ or $\sec [\eta]$, which vary slowly for moderate values of $\eta$. In such cases, the arithmetic mean $1/2([\phi] + [\theta])$ of the angles $[\phi]$ and $[\theta]$ serves as a sufficient approximation for $\eta$ over an arc of moderate extent.

## Related Ballistic Calculations
The broader mathematical framework for these trajectories involves several integral relationships:
* Time ($t$) is calculated as $t = C[T(U) - T(u)]$.
* Horizontal distance ($x$) is calculated as $x = C \cos [\eta] [S(U) - S(u)]$.
* Vertical distance ($y$) is calculated as $y = C \sin [\eta] [S(U) - S(u)]$.
* The difference in angles is expressed as $\tan [\phi] - \tan [\theta] = C \sec [\eta] [I(U) - I(u)]$.

Practical applications of these methods have been documented by military officers. Lieutenant A. H. Wolley-Dod, R.A., provided a trajectory calculation in 1888 using Siacci's method with approximately twenty arcs. Captain Ingalls achieved accurate results by assuming a mean tenuity-factor $[\tau] = 0.68$ (corresponding to a height of about 2 m) and working in two arcs over the trajectory—one up to the vertex and one down.

## Sources
Compiled from: britannica11 vol02b baconthorpe to bankruptcy
---
*Written by the AI Librarian strictly from the public-domain books of the archive. Topic memory: data/written-topics.json*
