# Graphic Method of Finding Deflection

The graphic method for determining the deflection of a beam involves the construction of a distorted curve based on the radii of curvature of various sections of the span. This process allows a draughtsman to visually represent and then calculate the actual deflection of a structure, such as a bridge.

## Procedure for Construction
To employ this method, the span $L$ is divided into a convenient number $n$ of equal parts, each with a length $l$, such that $nl = L$. The radii of curvature ($R_1, R_2, R_3$, etc.) are then computed for the various sections of the beam.

To translate these measurements onto paper, a scale is established where $L_1$ and $l_1$ represent the lengths to be drawn, defined by the relationship $L = aL_1$. A series of radii ($r_1, r_2, r_3$, etc.) is then created using the formula $r = R/ab$, where $b$ is a constant chosen to ensure the resulting arcs can be drawn using available draughtsman's tools.

The curve is constructed using arcs of length $l_1, l_2, l_3$, etc., corresponding to the radii $r_1, r_2$, etc. Because the radius is infinite for a length of $1/2l_1$ at each end of the span, the curve must conclude with a straight line that is tangent to the final arc.

## Calculation of Actual Deflection
Once the curve is drawn, the measured deflection of this graphic curve from the straight line is denoted as $v$. The actual deflection of the bridge, denoted as $V$, is then calculated approximately using the formula:
$V = av/b$

## Vertical Distortion and Scaling
This graphic method intentionally distorts the curve; the vertical ordinates are drawn to a scale that is $b$ times greater than the horizontal ordinates. 

For example, if a beam 100 feet in length is drawn at a horizontal scale of one-tenth of an inch to the foot, $a$ equals 120, and the beam is represented as 10 inches on paper. If the true radius at the center of the beam is 10,000 feet, an undistorted drawing would require a radius of 1,000 inches. However, by setting the constant $b$ to 50, the draughtsman can instead draw the curve with a manageable radius of 20 inches.

It is necessary to regulate the value of $b$ to ensure that the vertical distortion does not become so extreme that a sensible difference emerges between the length of the chord and the length of the arc.

## Related Concepts of Deflection
In the broader context of girder deflection, the deviation $y$ of the neutral axis from the axis $OX$ is given by the relation $d^2y/dx^2 = M/EI$, where $M$ is the bending moment, $I$ is the amount of inertia of the beam at point $D$, and $E$ is the coefficient of elasticity. The radius of curvature $R$ at point $D$ is defined as $R = EI/M$.

For a beam supported at the ends and loaded with $w$ per inch length, where $a$ is the half span, the bending moment is $M = w(a^2 - x^2)$. In such cases, the deflection at the center ($\delta$) is calculated as:
$\delta = 5wa^4 / 24EI$

To ensure a girder becomes straight under its working load, it is constructed with a camber, or upward convexity, equal to the calculated deflection. For riveted girders, a modulus of elasticity ($E$) of approximately 17,500,000 lb per sq. in. is used for first loading to account for the yielding of joints.

## Sources
Compiled from: britannica11 vol03a brequigny to bulgaria
---
*Written by the AI Librarian strictly from the public-domain books of the archive. Topic memory: data/written-topics.json*
