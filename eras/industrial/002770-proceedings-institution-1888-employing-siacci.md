# Lieutenant A. H. Wolley-Dod and the Proceedings R.A. Institution (1888)

## Ballistic Calculations and Siacci's Method
In the 1888 volume of the *Proceedings R.A. Institution*, Lieutenant A. H. Wolley-Dod, R.A., provided a calculation of a trajectory. To achieve this, Wolley-Dod employed the method developed by Colonel Siacci of the Italian artillery, utilizing approximately twenty arcs.

Siacci's method is generally employed for "high angle fire" (defined officially as fire at elevations greater than 15 degrees) and "curved fire" (fire from howitzers at all angles of elevation not exceeding 15 degrees). In these instances, the curvature of the trajectory is considerable, necessitating modifications to the formulae used in direct fire. The method begins with the exact equations of motion in a resisting medium.

## Technical Application of Siacci's Functions
The method utilizes specific functions—T, S, I, and D—from the ballistic table. For direct fire, these functions are applied as follows:
*   The integral of $du/f(u)$ is expressed as $T(U) - T(u)$.
*   The integral of $u \, du/f(u)$ is expressed as $S(U) - S(u)$.
*   The integral of $g \, du/u f(u)$ is expressed as $I(U) - I(u)$.

These equations were slightly modified by General Mayevski. In numerical applications involving high angle fire, the ballistic table for direct fire remains applicable.

## The Altitude-Function and Trajectory Analysis
A key component of this ballistic approach is Siacci's altitude-function, $A$ or $A(u)$. This function allows for the calculation of $y/x$ without the need to introduce $\sin [\eta]$ or $\tan [\eta]$. Instead, $[\eta]$ appears only as $\cos [\eta]$ or $\sec [\eta]$, which vary slowly for moderate values of $[\eta]$. Consequently, $[\eta]$ does not require extreme accuracy; the arithmetic mean of $[\phi]$ and $[\theta]$—expressed as $1/2([\phi] + [\theta])$—is sufficient for any arc of moderate extent.

The altitude-function $A$ is calculated via summation from the finite difference $[\Delta]A$, where $[\Delta]A = I(u) [\Delta]S$ (or $I(u) u[\Delta]u / gp$).

## Utility in Direct Fire
Siacci's altitude-function is also useful in direct fire for the immediate determination of the angle of descent $[\beta]$ and the angle of elevation $[\phi]$ required for a specific range of $X$ ft. or $R$ yds., between velocity limits $v$ and $V$. 

In direct fire, the real velocities ($V$ and $v$) and pseudo-velocities ($U$ and $u$) are undistinguishable. In these cases, $\sec [\eta]$ may be replaced by unity. For small angles, the following relationships are used:
*   $\sin 2[\phi] = 2C [I(V) - [\Delta]A/[\Delta]S]$
*   $\sin 2[\beta] = 2C [[\Delta]A/[\Delta]S - I(v)]$

## Comparative Ballistic Results
While Lieutenant Wolley-Dod used Siacci's method with twenty arcs, other practitioners used different assumptions. Captain Ingalls, for example, assumed a mean tenuity-factor $[\tau] = 0.68$, which corresponds to a height of about 2 m. Based on the estimate that the shot would reach a height of 3 m., Ingalls obtained a very accurate result by working in only two arcs over the entire trajectory—one up to the vertex and one down again.

## Sources
Compiled from: britannica11 vol02b baconthorpe to bankruptcy
---
*Written by the AI Librarian strictly from the public-domain books of the archive. Topic memory: data/written-topics.json*
