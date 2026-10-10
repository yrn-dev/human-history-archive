# Greatest Bending Moment due to Travelling Concentrated Loads

The calculation of the greatest bending moment caused by travelling loads is a critical aspect of girder and bridge design. Depending on the nature of the load—whether it is uniform or concentrated—and the length of the bridge, different mathematical methods and criteria are employed to determine the maximum stress at any given section.

## Uniform Travelling Loads
For a travelling live load of $w$ per foot advancing from the left abutment, the bending moment at a section $C$ (located at distance $m$ from the left abutment) increases as the load advances. If the center of the load is at distance $x$ from the left abutment, the reaction at $B$ is $2wx^2/l$ and the bending moment at section $C$ is $2wx^2/(l-m)/l$. 

For uniform travelling loads, the bending moments reach their maximum value when the loading of the span is complete. In this state, the loads on either side of section $C$ are proportional to $m$ and $l-m$. For a girder of span $l$ carrying a uniform load $w$ per foot run, the greatest bending moment occurs at the center and is equal to $M_c = 1/8wl^2$. At any point $x$ from the abutment, the bending moment follows the equation of a parabola: $M = 1/2wx(l-x)$.

## Concentrated Travelling Loads
When a series of travelling loads at fixed distances pass over a girder, the bending moment at a section $C$ is determined by the resultants of the loads on either side of that section. If $W_1$ and $W_2$ are resultants at distances $x$ and $x+a$ from the left abutment, the reaction at $B$ is $W_1x/l + W_2(x+a)/l$. The bending moment at $C$ is expressed as $M = W_1x(l-m)/l + W_2m\{1-(x+a)/l\}$.

If these loads move a distance $\Delta x$ to the right, the change in bending moment ($\Delta m$) is $W_1\Delta x(l-m)/l - W_2\Delta x m/l$. This indicates that the bending moment increases if $W_1(l-m) > W_2m$, or if $W_1/m > W_2/(l-m)$. These ratios represent the average loads per foot run to the left and right of section $C$. Consequently, the maximum bending moment at $C$ occurs when the average load is the same on either side of the section.

The general criterion for the position of loads to produce the greatest moment at $C$ is that one load must be located at $C$ (with the load at $C$ neglected for the average calculation), and the other loads must be distributed so that the average loads per foot on either side are nearly equal. Generally, one of the largest loads must be at $C$.

## Design Methods for Bridges
The approach to determining maximum bending moments varies by bridge length:

*   **Short Bridges:** It is best to draw the curve of maximum bending moments for a typical assumed set of loads and design the girder based on that curve.
*   **Longer Bridges:** The funicular polygon provides a more convenient method for determining maximum bending moments.

Because railway rolling stock varies significantly, precise magnitudes of loads cannot be known. Engineers instead assume a set of loads likely to produce severer straining than probable actual loads. For most cases (excluding very short bridges or very unequal loads), a parabola can be used to encompass the curve of maximum moments. This parabola represents the curve for a travelling load uniform per foot run. The load per foot that produces this parabola is termed the uniform load per foot equivalent ($w_e$) to the assumed set of concentrated loads. For practical design, $w_e$ can be found by using a parabola that has the same ordinate as the curve of maximum moments at either the center of the span or at one-quarter span.

## Influence Lines
An influence line is a tool used to investigate the action of travelling loads. The abscissa of the line represents the distance of a load from one end of the girder, and the ordinate represents the bending moment or shear at a specific section due to that load. Usually, these lines are drawn for a unit load.

For a girder $A'B'$ and a section $C'$, if a unit load is at $F'$, the reaction at $B'$ is $m/l$ and the moment at $C'$ is $m(l-x)/l$. By repeating this for all positions of the load, an influence line $AGB$ is created; the area $AGB$ is known as the influence area. The greatest moment $CG$ at $C$ is $x(l-x)/l$. To find the maximum moment at $C$ for a series of loads ($P_1, P_2, P_3...$) at distances $m_1, m_2...$, the distances are set off along the line and the corresponding ordinates ($y_1, y_2...$) of the influence curve are used to calculate the total moment.

## Sources
Compiled from: britannica11 vol03a brequigny to bulgaria
---
*Written by the AI Librarian strictly from the public-domain books of the archive. Topic memory: data/written-topics.json*
