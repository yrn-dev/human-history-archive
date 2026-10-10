# Reaction at the Right Abutment

In the study of bridge engineering and the determination of stresses in members, the reaction at the right abutment is a critical value used to calculate shearing forces and bending moments within a girder. The calculation of this reaction varies depending on the type of load applied to the span and whether those loads are fixed or travelling.

## Fixed Loads on Girders
For a girder of span $l$ supported at both ends, the reaction at the right abutment ($R_2$) depends on the nature of the load:

*   **Concentrated Fixed Load:** If a fixed load $W$ is positioned at a distance $m$ from the right abutment, the reaction at the right abutment is $R_2 = W(l-m)/l$.
*   **Uniform Fixed Load:** If the girder carries a uniform load $w$ per foot run, the total load is $wl$. In this instance, the reactions at both abutments are equal, meaning $R_1 = R_2 = \frac{1}{2}wl$.
*   **Multiple Concentrated Loads:** For a beam with a system of loads $W_1, W_2, \dots W_n$, the reaction at the right abutment is calculated as $R_2 = W_1x_1/l + W_2x_2/l + \dots$, where $x$ represents the distance of the loads from the left abutment.

## Travelling Concentrated Loads
When loads move across a girder from the left abutment, the reaction at the right abutment (often designated as point B) changes based on the position of the loads:

*   **Uniform Travelling Load:** For a load of $w$ per foot run advancing from the left, if its centre is at distance $x$ from the left abutment, the reaction at B is $2wx^2/l$.
*   **Series of Travelling Loads:** For a series of travelling loads at fixed distances apart, let $W_1$ and $W_2$ be the resultants on either side of a section $C$, located at distances $x$ and $x+a$ from the left abutment. The reaction at B is $W_1x/l + W_2(x+a)/l$.
*   **Resultant Loads:** If a set of concentrated loads advances from the left and $R$ is the resultant of the loads currently on the bridge when the first load $W_1$ is at section $C$ (at distance $n$ from the left), the reaction at B is $Rn/l$.

## Influence Lines and Shear
The reaction at the right abutment is frequently used to determine the shear at a specific section of the girder. For a unit load positioned at $F'$, the reaction at the right abutment $B'$ is $m/l$. 

In cases where a rail girder distributes a unit weight to cross girders at $D'$ and $E'$, the reaction at $B'$ is calculated as $\{(p-n)x_1 + n(x_1+p)\}/pl$, where:
*   $n$ is the distance of the load from $D'$.
*   $x_1$ is the distance of $D'$ from the left abutment.
*   $p$ is the length of a bay.

## Special Cases and Other Structures
The calculation of abutment reactions differs for specific bridge types and materials:

*   **Rolling Bridges:** These girders are longer than the span. The portion overhanging the abutment is counter-weighted so that the centre of gravity remains over the abutment during forward rolling.
*   **Bascule Bridges:** In these structures, a leaf turns around a horizontal hinge at one abutment. When closed, the bridge is supported by abutments at each end.
*   **Masonry and Brickwork Arches:** For rigid blockwork structures, finding abutment reactions requires the use of assumptions and principles such as the principle of least action. However, if hinges are introduced at the springings and crown, the calculation of stresses becomes simpler as the line of pressures must pass through these hinges.

## Sources
Compiled from: britannica11 vol03a brequigny to bulgaria
---
*Written by the AI Librarian strictly from the public-domain books of the archive. Topic memory: data/written-topics.json*
