# Shear Due to Travelling Loads

In the engineering of girders, the analysis of shearing force is critical for determining the necessary strength of the girder web. When a girder is subjected to travelling loads, such as a railway train, the distribution of shear changes as the load moves across the span.

## Uniform Travelling Loads
For a girder with a span of $2c$, consider a uniform train weighing $w$ per foot run advancing from the left abutment. When the train covers the girder to a distance $x$ from the center, the total load is $w(c+x)$. The reaction at the abutment $B$ is calculated as $R_2 = w(c+x) \times (c+x)/4c$, which simplifies to $w/4c(c+x)^2$. This reaction also represents the shearing force at point $C$ for that specific position of the load.

As the load travels, the shear at the head of the train is represented by the ordinates of a parabola with its vertex at $A$ and a maximum value of $F_{max} = -½wl$ at $B$. If the load travels in the reverse direction, the shearing force at the head of the train follows the ordinates of a dotted parabola. The maximum shear at $C$ occurs when the head of the train is positioned exactly at $C$.

## Concentrated and Distributed Loads
When a set of concentrated loads at fixed distances advances from the left abutment, the greatest shear at a specific section $C$ may occur when the first load ($W_1$) is at $C$. If $W_1$ passes beyond $C$, the maximum shear may then occur when the second load ($W_2$) reaches $C$. 

If $R$ is the resultant of the loads on the bridge when $W_1$ is at $C$, the shear at $C$ is $Rn/l$. When the loads advance a distance $a$ to bring $W_2$ to $C$, the shear becomes $R(n+a)/l - W_1$, plus any reaction $d$ at $B$ from additional loads entering the girder. The shear increases by moving $W_2$ to $C$ if $Ra/l + d > W_1$.

This calculation is modified if the load is distributed to bracing intersections via rail and cross girders. For instance, if the action of $W$ is distributed to $A$ and $B$ by flooring, the loads at $A$ and $B$ are $W(p-x)/p$ and $Wx/p$. In this scenario, moving $W_2$ to $C$ increases shear if $Ra/l > W_1$ (when $a > p$) or if $Ra/l > W_1a/p$ (when $a < p$), neglecting $d$.

## Influence Lines and Eddy's Method
The influence line for shear at $C$ is used to determine the total shear $S$ produced by a series of loads $P_1, P_2, \dots$ at distances $m_1, m_2, \dots$ from the left abutment. The total shear is the sum $S = P_1y_1 + P_2y_2 + \dots$, where $y$ represents the ordinates of the influence curve under the loads. Generally, the greatest shear at $C$ occurs when the longer of the two segments created by $C$ is fully loaded and the other is unloaded, with the leading load positioned at $C$.

Prof. H.T. Eddy proposed a method for investigating maximum shear using a geometric construction. By laying off horizontal lines equal to the span $l$ and drawing verticals at the abutments, the reaction at $A$ (and thus the shear at any point of $AC$) can be determined as $mn = W(l-x)/l$. As the load moves to a new position $D$ at distance $x+a$, the new reaction at $A$ is $ro = W(l-x-a)/l$, while the shear on $DB$ is $rs = W(x+a)/l$.

## Dead Loads and Counterbracing
Girders typically support both a dead load ($w_l$ per foot run) and a live travelling load. The total shear is the sum of the dead load shear and the maximum travelling load shear of the same sign. 

In girders with braced webs where tension bars cannot resist thrust, the position of the live load is critical. For a train advancing from the left, the travelling load shear in the left half of the span has a different sign than the shear produced by the dead load. Near the middle of the girder, the shear changes sign depending on whether the load advances from the left or the right. Consequently, bracing bars in this region must be designed to resist both tension and thrust, as the range of stress is the sum of the stresses from loads advancing from either direction.

## Sources
Compiled from: britannica11 vol03a brequigny to bulgaria
---
*Written by the AI Librarian strictly from the public-domain books of the archive. Topic memory: data/written-topics.json*
