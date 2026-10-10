# Greatest Shear when Concentrated Loads Travel over the Bridge

The determination of the greatest shear at a specific section of a bridge girder subjected to moving concentrated loads requires an analysis of the loads' positions as they advance across the span. This process involves calculating the reaction at the supports and the resulting shearing force at the section of interest.

## Calculation for Concentrated Loads
To find the greatest shear at a section (C) when a set of concentrated loads at fixed distances advances from the left abutment, engineers evaluate the position of the loads relative to that section. The maximum shear at C may occur when the first load ($W_1$) is located exactly at C. In this scenario, if $R$ represents the resultant of the loads currently on the bridge, the reaction at the support (B) and the shear at C is expressed as $Rn/l$.

As the loads continue to advance, the shear at C may increase when the second load ($W_2$) reaches the section. If the loads advance a distance $a$ to bring $W_2$ to C, the shear at C becomes $R(n+a)/l - W_1$, plus any reaction $d$ at B caused by additional loads entering the girder during the movement. Because $d$ is generally small and negligible, the shear is increased by moving $W_2$ to C if $Ra/l + d > W_1$.

## Effects of Load Distribution
The results of shear calculations are modified if the load near the section is distributed to bracing intersections via cross girders and rails. For example, if the action of a load $W$ is distributed to points A and B by the flooring, the loads at A and B are $W(p-x)/p$ and $Wx/p$, respectively.

When determining the greatest shear at section C under these conditions, the calculation depends on the distance $a$ relative to the bay length $p$:
*   If $a > p$, the shear at C becomes $R(n+a)/l + d - W_1$.
*   If $a < p$, the shear at C becomes $R(n+a)/l + d - W_1a/p$.

Neglecting $d$, the shear increases by moving $W_2$ to C if $Ra/l > W_1$ in the first case, or if $Ra/l > W_1a/p$ in the second case.

## Influence Lines and Total Shear
An influence line is a tool used to investigate the action of travelling loads, where the abscissa represents the distance of a load from one end of the girder and the ordinate represents the shear or bending moment at a given section. For a unit load at $F'$, the reaction at $B'$ and the shear at $C'$ is $m/l$.

The total shear $S$ at section C due to a series of loads ($P_1, P_2, \dots$) at distances ($m_1, m_2, \dots$) from the left abutment is calculated as $S = P_1y_1 + P_2y_2 + \dots$, where $y$ represents the ordinates of the influence curve under the loads. Generally, the greatest shear at C occurs when the leading load is at C and the longer of the two segments into which C divides the girder is fully loaded while the other remains unloaded. If loads are unequally spaced or of very different magnitudes, a few trials are used to determine the position that yields the maximum value of $S$.

## Comparison with Uniform Loads
While concentrated loads require specific positional trials, a uniform train weighing $w$ per foot advancing over a girder of span $2c$ produces shear that can be mapped. When the train covers the girder to a distance $x$ from the center, the reaction at B (and the shearing force at C) is $R_2 = w/4c(c+x)^2$. The shear at the head of such a train follows the ordinates of a parabola with its vertex at A and a maximum $F_{max} = -½wl$ at B.

For a uniformly distributed load $w$ per foot run, the shear at C is determined by multiplying $w$ by the area of the influence curve under the segment covered by the load. If the load rests directly on the main girder, the greatest positive and negative shears at C are $w \times AGC$ and $-w \times CHB$, respectively.

## Sources
Compiled from: britannica11 vol03a brequigny to bulgaria
---
*Written by the AI Librarian strictly from the public-domain books of the archive. Topic memory: data/written-topics.json*
