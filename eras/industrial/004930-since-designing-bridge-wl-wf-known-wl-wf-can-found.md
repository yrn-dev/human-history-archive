# Bridge Design and Engineering

Bridge engineering requires the determination of loads to be carried and the proportioning of components to ensure that stresses do not exceed safe limits, which are sometimes prescribed by law. In modern metal bridges, every member has a calculated straining action and a definite function. As spans increase, the dead weight of the structure becomes a larger fraction of the total load, eventually imposing a limit on further increases in span due to the necessity of material economy.

## Girder Weight and Design Calculations
In the design of a bridge, the weight of the main girders ($W_g$) is required to carry their own weight as well as the combined load of $W_l + W_f$. This is expressed by the formula $W_g = (W_l + W_f)k / (1 - k)$. Because $W_l + W_f$ is known during the design process, the value of $k(W_l + W_f)$ can be determined using a provisional design that neglects the weight $W_g$. The final bridge must then have member sections larger than those in the provisional design by a ratio of $k / (1 - k)$.

Empirical relations provided by Waddell allow for the comparison of girder weights per foot run ($w_1, w_2$) for different spans ($l_1, l_2$) and live loads ($p, p'$). For instance, the ratio of weights for two different spans under the same live load is $w_2/w_1 = ½ [l_2/l_1 + (l_2/l_1)^2]$.

Unwin provided a partially rational approximate formula for the weight of main girders ($w_3$):
$w_3 = (w_1 + w_2)l^2 / (Cds - l_2) = (w_1 + w_2)lr / (Cs - lr)$
In this formula, $w$ is the total live load per foot run, $w_2$ is the platform weight per foot run, $l$ is the span, $s$ is the average stress on the gross section of metal, $d$ is the depth of the girder at the center, and $r$ is the ratio of span to depth ($l/d$). The constant $C$ varies by material: 1500 to 1800 for iron braced parallel or bowstring girders, and 1200 to 1500 for steel.

## Bending Moments and Load Analysis
For short bridges, engineers draw a curve of maximum bending moments based on assumed typical loads. For longer bridges, the funicular polygon is a more convenient method. Because railway rolling stock varies, engineers assume a set of loads that produce severer straining than probable actual loads.

A parabola can often be used to include the curve of maximum moments, representing a uniform travelling load per foot run ($w_e$). This $w_e$ is the uniform load equivalent to any assumed set of concentrated loads. The value of $w_e$ can be found by ensuring the parabola has the same ordinate as the curve of maximum moments at either the center of the span or at one-quarter span. For a girder of span $2c$, the bending moment at the center ($M_c$) is $½w_ec^2$, and at quarter span ($M_a$), it is $3/8w_ec^2$.

## Structural Types and Materials
The choice of girder type often depends on the span:
*   **Plate web girders:** Used for spans of less than 100 ft. In the United States, riveted plate girders are used up to 50 ft.
*   **Braced girders:** Riveted braced girders are used for spans of 50 ft. to 75 ft.
*   **Pin-connected girders:** Used for longer spans.
*   **Other types:** Cantilever bridges have seen extensive use since the erection of the Forth bridge, alongside steel arch and suspension bridges.

In plate web girders, the ratio of depth to span is economically limited to between 1/15 and 1/12. While deeper girders reduce stress in the flanges, they require a heavier web to prevent buckling and resist corrosion. Open web, lattice, or braced girders are generally more economical for spans larger than those suited for solid web girders.

## Substructure and Support
The substructure consists of foundations, abutments, and piers, typically constructed from concrete, brickwork, or stone masonry, though intermediate piers may occasionally use woodwork or metal. The design of these supports depends on the superstructure:
*   **Girders:** Resultant pressure on piers or abutments is vertical.
*   **Arches:** Abutments must transmit resultant thrust in a safe direction and distribute it to avoid undue compression. Intermediate piers must be stable enough to counterbalance thrust when one arch is loaded and the other is not.
*   **Suspension Bridges:** The anchorage abutment must be stable under the maximum pull of the chains.

## Notable Examples
*   **London Bridge (completed 1831):** A masonry arch structure designed by John Rennie the elder and Sir John Rennie. It features semi-elliptical arches with a center span of 152 ft. and a total length of 1005 ft. The foundations are approximately 29 ft. 6 in. below low water.
*   **Victoria Falls Bridge (completed 1905):** Designed by Sir Douglas Fox, this 650 ft. bridge combines a girder and a parabolic arch. The center arch has a span of 500 ft. and a rise of 90 ft.

## Sources
Compiled from: britannica11 vol03a brequigny to bulgaria
---
*Written by the AI Librarian strictly from the public-domain books of the archive. Topic memory: data/written-topics.json*
