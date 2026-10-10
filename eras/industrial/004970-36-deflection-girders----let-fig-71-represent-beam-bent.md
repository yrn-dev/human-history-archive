# Deflection of Girders

The deflection of girders refers to the bending of a beam under the influence of external loads. This process is analyzed through mathematical relations, graphic methods, and practical construction adjustments to ensure structural integrity.

## Mathematical Analysis of Deflection
When a beam is bent by external loads, the deviation of the neutral axis (represented as $y = DE$) from the axis $OX$ at any point $D$ is determined by the relation $d^2y/dx^2 = M/EI$. In this equation, $M$ represents the bending moment, $I$ is the amount of inertia of the beam at point $D$, and $E$ is the coefficient of elasticity. For the purposes of deflection calculations, it is typically considered accurate enough to treat $I$ as a constant for the length of the beam, using the moment of inertia at the beam's center.

The integration of this relation allows for the calculation of deflection when $M$ is expressed in terms of $x$. For a beam that is loaded with $w$ per inch length and supported at the ends, the bending moment is $M = w(a^2-x^2)$, where $a$ is the half span. In such a case, the deflection at the center ($\delta$) is calculated as $\delta = 5wa^4/24EI$. Additionally, the radius of curvature of the beam at point $D$ is defined by the relation $R = EI/M$.

## Graphic Method of Finding Deflection
A graphic approach can be used to determine deflection by dividing the span $L$ into $n$ equal parts of length $l$ ($nl = L$). The radii of curvature ($R_1, R_2, R_3$, etc.) are computed for the various sections. These are then represented on paper using a scale where $L = aL_1$ (with $L_1$ being the length drawn on paper). 

To facilitate drawing, a series of radii $r$ is used such that $r_1 = R_1/ab$, where $b$ is a constant chosen to allow the arcs to be drawn with available tools. A curve is then drawn using arcs of length $l_1, l_2, l_3$, etc., with the corresponding radii $r_1, r_2$, etc. Because the radius is infinite for a length of $1/2l_1$ at each end, the curve ends with a straight line tangent to the last arc. The actual deflection of the bridge ($V$) is then approximately $V = av/b$, where $v$ is the measured deflection of the drawn curve from a straight line. This method involves vertical distortion, as vertical ordinates are drawn to a scale $b$ times greater than horizontal ordinates. To avoid a sensible difference between the length of the arc and its chord, the value of $b$ must be regulated.

## Camber and Elasticity
To ensure a girder becomes straight under its working load, it is constructed with a camber, which is an upward convexity equal to the calculated deflection. 

The modulus of elasticity varies depending on the material and construction. For a solid bar, a standard modulus is used, but for riveted girders, a smaller modulus of elasticity is taken to account for the yielding of joints during the first loading; for these girders, $E$ is approximately 17,500,000 lb per sq. in. W.J.M. Rankine provides an approximate rule for working deflection: $\delta = l^2/10,000h$, where $l$ is the span and $h$ is the depth of the beam, based on stresses usual in bridgework from total dead and live loads.

## Impact and Vibration
The stresses and deflections of girders are affected by how loads are applied. If a vertical load is imposed suddenly without velocity, the stress and deformation are momentarily double those of a load at rest. In practice, loads applied to bridges often increase deflection with speed, creating vibrations about a mean position. These are caused by factors such as:
* Unbalanced moving parts of the engine acting vertically.
* Centrifugal and lurching actions caused by rails that are not perfectly smooth or straight.
* Shocks resulting from inequalities of level at rail ends.

Impact increments are generally larger on short main girders than on long ones, and larger on flooring girders than on main girders. Research by E.H. Stone indicates that the increment of deflection due to impact depends on the ratio of dead to live load. 

Observations by S.W. Robinson and F.E. Turneaure regarding moving trains show that locomotive balance weights significantly cause vibration. At speeds below 25 m. an hour, vibration is minimal. However, at 40 or 50 m. an hour, the increase in deflection due to impact can reach 40% to 50% for girder spans under 50 ft., decreasing to about 25% for 75-ft. spans. While the speed of the train affects the magnitude of vibrations, it does not affect the mean deflection.

## Sources
Compiled from: britannica11 vol03a brequigny to bulgaria, britannica11 vol05b carnegie to casus belli
---
*Written by the AI Librarian strictly from the public-domain books of the archive. Topic memory: data/written-topics.json*
