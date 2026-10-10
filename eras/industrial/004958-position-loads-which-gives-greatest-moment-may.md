# Position of Loads for Maximum Bending Moment at C

In the study of girders and beams subjected to travelling loads, determining the specific position of loads that produces the greatest bending moment at a given section, denoted as C, is a critical engineering calculation. This is achieved through the application of specific criteria regarding load distribution and the use of influence lines.

## The Criterion for Maximum Bending Moment
For a series of travelling loads, the bending moment at section C increases if the average load per foot run to the left of C is greater than the average load per foot run to the right. Specifically, if $W_1$ and $W_2$ represent these average loads and $l$ is the span with $m$ being the distance to the section, the moment increases if $W_1(l-m) > W_2m$, or $W_1/m > W_2/(l-m)$.

Consequently, the maximum bending moment at C occurs when the average load is the same on either side of the section. To satisfy this condition, the following criterion is applied:
* One load must be positioned exactly at C.
* The remaining loads must be distributed such that the average loads per foot on either side of C (neglecting the load positioned at C) are nearly equal.

Generally, to maximize the moment, one of the largest loads in the series should be placed at C, with other loads distributed to the left and right to maintain the equality of average loads. In cases where loads are very unequal in magnitude or distance, multiple positions may satisfy this condition, requiring further ascertainment to find the absolute maximum.

## Alternative Statement of the Criterion
The criterion for the greatest bending moment can be expressed through the relationship between the loads on the bridge. If a series of loads travels from the right and $W_x$ is the load at the section when the moment is greatest, and $W_n$ is the last load to the right still on the bridge, the position must satisfy a condition where the sum of loads $W_1$ through $W_{x-1}$ multiplied by $x$ is greater than $l$ multiplied by the sum of all loads $W_1$ through $W_n$ divided by $x$, while the sum of loads $W_1$ through $W_x$ multiplied by $x$ is less than that same value.

## Influence Lines and Area
The investigation of maximum moments is facilitated by an "influence line." This line uses the distance of a load from one end of the girder as the abscissa and the resulting bending moment or shear at a given section as the ordinate. For a unit load at position $F'$, the moment at $C'$ is $m(l-x)/l$. 

When dealing with a uniform travelling load $w$ per foot of span, the moment at C is calculated as $w$ multiplied by the area of the influence curve under the portion of the girder covered by the load. If the load is distributed via a rail girder (stringer) to bracing intersections $D'E'$, the influence line for that specific bay is altered. In such a configuration, a unit load at distance $n$ from $D'$ results in a load of $(p-n)/p$ at $D'$ and $n/p$ at $E'$, where $p$ is the length of the bay.

## Application to Different Bridge Types
The method for determining maximum moments varies based on the length of the bridge:
* **Short Bridges:** It is recommended to draw a curve of maximum bending moments based on a typical set of assumed loads and design the girder accordingly. In cases of very unequal loads, moments are typically greatest at sections under the heaviest load (e.g., a 15-ton load).
* **Longer Bridges:** The funicular polygon is often a more convenient method for determining maximum bending moments.

For most bridges (excluding very short ones with very unequal loads), a parabola can be used to encompass the curve of maximum moments. This parabola represents the curve for a travelling load that is uniform per foot run. This "equivalent uniform load" ($w_e$) can be approximated by finding a parabola that has the same ordinate at the centre of the span or at one-quarter span as the actual curve of maximum moments.

## Sources
Compiled from: britannica11 vol03a brequigny to bulgaria
---
*Written by the AI Librarian strictly from the public-domain books of the archive. Topic memory: data/written-topics.json*
