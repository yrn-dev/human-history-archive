# Determination of Shear in Bridge Girders

In the engineering of beam girder or truss bridges, the determination of stresses in the main girders is a primary requirement. A main girder is typically composed of a vertical web and an upper and lower flange (also referred to as a boom or chord). While the flanges are designed to carry horizontal tension and compression, the vertical web is responsible for resisting the vertical loading forces and the equal horizontal shearing forces in the case of a plate web.

## Calculation of Total Shear at a Section

To determine the total shear at any given section $ab$ of a beam, the reactions at the abutments must first be established. For a beam with a system of loads $W_1, W_2, \dots W_n$, the reaction at the right abutment ($R_2$) is calculated as $W_1x_1/l + W_2x_2/l + \dots$, and the reaction at the left abutment ($R_1$) is the sum of all loads minus $R_2$.

The total shear ($S$) at section $ab$ is defined by the formula $S = R - \sum(W_1 + W_2 \dots)$, where the summation includes all loads located to the left of the section. Similar results are obtained if the loads to the right of the section are considered instead.

## Distribution of Shearing Force

The distribution of shearing force varies based on the type of load applied to the girder:

*   **Fixed Concentrated Load:** For a girder of span $l$ with a fixed load $W$ placed at distance $m$ from the right abutment, the reactions are $R_1 = Wm/l$ and $R_2 = W(l-m)/l$. The shears on vertical sections to the left and right of the load are $R_1$ and $-R_2$, respectively, resulting in a distribution represented by two rectangles.
*   **Uniform Load:** For a girder carrying a uniform load $w$ per foot run, the total load is $wl$, and the reactions at the abutments are $R_1 = R_2 = \frac{1}{2}wl$. In this instance, the distribution of shear on vertical sections is represented by the ordinates of a sloping line.

## Shear Due to Travelling Loads

When loads move across a bridge, the shear at a specific section $C$ changes. For a set of concentrated loads at fixed distances advancing from the left, the greatest shear at $C$ often occurs when a specific load (such as $W_1$ or $W_2$) is positioned at $C$. If the loads are distributed to bracing intersections by rail and cross girders, the calculation is modified based on whether the distance $a$ is greater or less than the distance $p$.

For a uniform train weighing $w$ per foot run advancing over a girder of span $2c$, the shear at the head of the train is represented by the ordinates of a parabola. The maximum shear occurs when the head of the train is at section $C$. It is noted that for travelling loads, such as railway trains, the maximum shear is greater for partial loading than for complete loading.

## Influence Lines and Eddy's Method

Influence lines are used to determine the shear at a section $C'$ due to a unit load placed anywhere on the girder. For a unit load at $F'$, the shear at $C'$ is $m/l$. The total shear $S$ due to a series of loads $P_1, P_2, \dots$ is calculated as $S = P_1y_1 + P_2y_2 + \dots$, where $y$ represents the ordinates of the influence curve under the loads. Generally, the greatest shear at $C$ occurs when the longer of the two segments created by $C$ is fully loaded and the leading load is at $C$.

An alternative approach, known as Eddy's Method (developed by Prof. H.T. Eddy in 1890), uses a geometric construction to investigate maximum shear. By laying off horizontal lines equal to the span $l$ and drawing verticals at the abutments and the load position, the reaction at the abutments and the resulting shear at any point can be determined via the properties of the resulting rectangles.

## Structural Implications of Shear

The web of a girder must be designed to resist the maximum shear. In girders with braced webs where tension bars cannot resist thrust, the direction of the travelling load is critical. For a train advancing from the left, the travelling load shear in the left half of the span may be of a different sign than the shear produced by the dead load. Consequently, bracing bars in the middle of the girder must be adapted to resist both tension and thrust.

In terms of material intensity, the shearing stress ($f_x$) in a plate web is calculated as $f_x = S/A$, where $A$ is the area of the plate web in a vertical section. For a braced web, the vertical component of the stress in the web bars must equal $S$. In composite structures of steel and concrete, the working shearing stress for concrete is generally taken as 75 lb per sq. in.

## Sources
Compiled from: britannica11 vol03a brequigny to bulgaria
---
*Written by the AI Librarian strictly from the public-domain books of the archive. Topic memory: data/written-topics.json*
