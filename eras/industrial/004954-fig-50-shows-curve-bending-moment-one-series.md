# Bending Moment in Girders and Bridges

The study of bending moments is central to the design of girders and bridges, particularly when dealing with fixed loads, uniform loads, and travelling loads. The bending moment refers to the internal stress created when external forces are applied to a structural member.

## Fixed and Uniform Loads
For a girder of span $l$ supported at its ends, the distribution of bending moment varies based on the type of load applied. When a fixed load $W$ is placed at a distance $m$ from the right abutment, the reactions at the abutments are $R_1 = Wm/l$ and $R_2 = W(l-m)/l$. In this scenario, the bending moment increases uniformly from either abutment toward the load, reaching a maximum of $M = R_2m = R_1(l-m)$. This distribution is represented by the ordinates of a triangle.

In contrast, a girder carrying a uniform load $w$ per foot run results in a total load of $wl$, with reactions at the abutments being $R_1 = R_2 = ½wl$. The greatest bending moment occurs at the center of the span and is calculated as $M_c = 1/8wl^2$. At any point $x$ from the abutment, the bending moment is $M = ½wx(l-x)$, which follows the equation of a parabola.

## Travelling Concentrated Loads
When loads move across a girder, the bending moment at any given section changes. For a series of travelling loads at fixed distances passing from the left, the maximum bending moment at a specific section $C$ occurs when one of the largest loads is positioned at $C$ and the remaining loads are distributed such that the average loads per foot on either side of $C$ (neglecting the load at $C$) are nearly equal.

If the average load to the left of a section is greater than that to the right, moving the loads to the right increases the bending moment, and vice versa. For a series of loads $W_1, W_2, \dots, W_n$, the position for the greatest bending moment at a section $ab$ is satisfied when the following condition is met:
$\frac{x(W_1+W_2+\dots+W_{x-1})}{l(W_1+W_2+\dots+W_n)} < \text{condition} < \frac{x(W_1+W_2+\dots+W_x)}{l(W_1+W_2+\dots+W_n)}$

## Analysis of Bending Moment Curves
The behavior of bending moments under travelling loads can be visualized through specific curves:

*   **Individual and Total Moments:** For loads $W_1, W_2, W_3$ traversing a girder at fixed distances $a$ and $b$, the bending moment due to each load is represented by the ordinates of triangles (e.g., $A'CB'$, $A'DB'$, and $A'EB'$). The total moment under $W_1$ is the sum of the intercepts these triangle sides cut from the vertical under $W_1$.
*   **Parabolic Paths:** As loads move, the points $C, D, E$ describe parabolas $M_1, M_2, M_3$, with middle ordinates of $¼W_1l, ¼W_2l$, and $¼W_3l$.
*   **Cumulative Curves:** The curve of bending moments under a leading load changes as more loads enter the girder. Initially, the curve $A"F$ represents moments due to $W_1$ only. As $W_1$ advances a distance $a$, the curve $FG$ represents moments due to $W_1$ and $W_2$. Finally, $GB"$ represents the moments for all three loads ($W_1+W_2+W_3$).

In extreme cases, such as short bridges with very unequal loads, the moments are greatest at the sections under the heaviest load (e.g., a 15-ton load).

## Design Applications and Equivalent Loads
For short bridges, designers typically draw the curve of maximum bending moments for a typical set of loads. For longer bridges, the funicular polygon is often a more convenient method. Because railway rolling stock varies, designers assume a set of loads likely to produce more severe straining than probable actual loads.

Except in cases of very short bridges or very unequal loads, a parabola can be found that includes the curve of maximum moments. This is the curve for a travelling load uniform per foot run. The load per foot run that produces this parabola is termed the uniform load per foot equivalent ($w_e$) to the assumed set of concentrated loads. Practical design often relies on a parabola that has the same ordinate at the center of the span or at one-quarter span as the curve of maximum moments.

## Influence Lines
Influence lines are used to investigate the bending moment or shear at a given section due to a unit load in any position on the girder. For a girder $A'B'$, the influence line for the bending moment at $C$ is created by plotting the moment $m(l-x)/l$ for all positions of a unit load. The area under this line is called the influence area, and the greatest moment $CG$ at $C$ is $x(l-x)/l$. To find the total moment due to multiple travelling loads $P_1, P_2, P_3 \dots$, the corresponding ordinates of the influence curve are summed.

## Sources
Compiled from: britannica11 vol03a brequigny to bulgaria, britannica11 vol04c bible to bisectrix
---
*Written by the AI Librarian strictly from the public-domain books of the archive. Topic memory: data/written-topics.json*
