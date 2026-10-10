# Radius of Curvature of the Beam at D

In the study of the deflection of girders, the radius of curvature of a beam at a specific point D is determined by the relationship between the material properties of the beam and the external forces acting upon it.

## Mathematical Relation for Radius of Curvature
For a beam bent by external loads, the radius of curvature at point D is expressed by the relation:
$R = EI/M$

In this formula, $M$ represents the bending moment, $I$ is the amount of inertia of the beam at point D, and $E$ is the coefficient of elasticity. In many deflection calculations, it is considered accurate enough to treat the moment of inertia ($I$) as a constant for the entire length of the beam, utilizing the value found at the center of the beam.

## Beam Deflection and the Neutral Axis
The deviation of the neutral axis of a bent beam at any point D from the axis OX is denoted as $y$ (or $y = DE$). This deviation is governed by the relation:
$d^2y/dx^2 = M/EI$

When $M$ is expressed in terms of $x$, integration can be performed to find the deflection. For example, in a beam supported at the ends and loaded with $w$ per inch length, the bending moment is $M = w(a^2 - x^2)$, where $a$ represents the half span. In such a case, the deflection at the center (where $x = a$) is calculated as:
$\delta = 5wa^4 / 24EI$

## Graphic Method for Finding Deflection
A graphic approach can be used to determine deflection by dividing the span $L$ into $n$ equal parts of length $l$ ($nl = L$). The radii of curvature ($R_1, R_2, R_3$, etc.) are computed for the various sections. To represent these on paper, a scale is applied where $L = aL_1$. A series of radii $r$ is then created such that $r_1 = R_1/ab, r_2 = R_2/ab$, and so on, where $b$ is a constant chosen to allow the arcs to be drawn using available draughtsman tools.

A curve is drawn using arcs of length $l_1, l_2, l_3$, etc., with the corresponding radii $r_1, r_2$, etc. It is noted that for a length of $1/2l_1$ at each end, the radius is infinite, requiring the curve to end with a straight line tangent to the final arc. The actual deflection of the bridge ($V$) is then approximately $V = av/b$, where $v$ is the measured deflection of the drawn curve from a straight line.

This graphic method involves a vertical distortion where vertical ordinates are drawn to a scale $b$ times greater than horizontal ordinates. To ensure accuracy, the value of $b$ must be regulated so that there is no sensible difference between the length of the arc and its chord.

## Sources
Compiled from: britannica11 vol03a brequigny to bulgaria
---
*Written by the AI Librarian strictly from the public-domain books of the archive. Topic memory: data/written-topics.json*
