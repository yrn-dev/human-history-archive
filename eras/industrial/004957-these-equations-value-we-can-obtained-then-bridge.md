# Bridge Design and Load Equations

## Bending Moments and Equivalent Load
In the design of bridge structures, specific equations are used to determine bending moments based on load distributions. The bending moment $M$ is expressed by the equation $M = ½w_e(c-x)(c+x)$. By applying specific values for $x$, different section moments can be identified:
*   For the centre section, where $x = 0$, the moment is $M_c = ½w_ec^2$.
*   For the section at quarter span, where $x = ½c$, the moment is $M_a = 3/8w_ec^2$.

From these equations, a value for the uniform equivalent load $w_e$ can be obtained. Once this value is established, the bridge is designed regarding direct stresses for bending moments resulting from both a uniform dead load and the uniform equivalent load $w_e$.

## Suspension Bridge Tension and Geometry
The analysis of suspension bridges involves calculating tension and the geometry of the supporting chain. The value $H$ represents the compression on the top flange or the maximum tension on the bottom flange of a girder with an equal span, similar loading, and a depth equal to the dip of the suspension bridge.

For any point $F$ on the curve at a distance $x$ from the vertex:
*   The horizontal component of the resultant remains unaltered.
*   The vertical component $V$ is the sum of the loads between the vertex $O$ and point $F$, expressed as $wx$.

In a triangle $FDC$ where $FD$ is tangent to the curve, $FC$ is vertical, and $DC$ is horizontal, the sides are proportional to the vertical force $V$, the resultant tension along the chain at $F$, and the horizontal tension at $O$. The relationship is defined as $H : V = DC : FC = wx²/2y : wx = x/2 : y$. This demonstrates that $DC$ is half of $OC$, which proves the curve is a parabola.

## Tension and Chain Length
The tension $R$ at any point at a distance $x$ from the vertex is determined by the equation $R^2 = H^2 + V^2 = w^2x^4/4y^2 + w^2x^2$, which simplifies to $R = wx\sqrt{1+x^2/4y^2}$. 

The angle $i$ between the tangent at any point (with coordinates $x$ and $y$ measured from the vertex) is given by $\tan i = 2y/x$. Additionally, the length of half the parabolic chain, denoted as $s$, is calculated as $s = x + 2y^2/3x$.

## Sources
Compiled from: britannica11 vol03a brequigny to bulgaria
---
*Written by the AI Librarian strictly from the public-domain books of the archive. Topic memory: data/written-topics.json*
