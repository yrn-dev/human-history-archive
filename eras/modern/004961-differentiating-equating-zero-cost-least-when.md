# Economic Span of a Bridge

In the engineering of bridges consisting of multiple spans, the determination of the "economic span" is the process of identifying the specific length of a span that results in the least overall cost for the structure.

## Cost Variables and Assumptions
To calculate the economic span, several cost factors are considered. The costs of the bridge flooring and the abutments are regarded as practically independent of the length of the span that is adopted. The primary variables that fluctuate based on the span length are the costs associated with the piers and the main girders.

The following variables are used to define the total cost:
*   **L**: The total length of the bridge between the abutments.
*   **l**: The length of one individual span.
*   **n**: The number of spans, which is approximately $L/l$.
*   **P**: The cost of one pier. This cost does not vary materially with the span adopted, as it depends primarily on the height of the bridge and the character of the foundations.
*   **G**: The cost of the main girders for one span, erected.

## The Relationship Between Span and Girder Cost
The cost of the main girders for a single span ($G$) varies nearly as the square of the span for any given intensity of live load and type of girder. This relationship is expressed by the formula $G = al^2$, where $a$ represents a constant.

## Calculating the Least Cost
The total cost ($C$) of the parts of the bridge that vary according to the adopted span is the sum of the cost of the piers and the cost of the main girders. This is expressed as:
$C = (n-1)P + nG$

Substituting the previously defined variables ($n = L/l$ and $G = al^2$), the equation becomes:
$C = LP/l - P + Lal$

To find the point where the cost is least, the equation is differentiated and equated to zero:
$dC/dl = -LP/l^2 + La = 0$

Solving this equation reveals that the cost is at its minimum when $P = al^2$, which means $P = G$. Therefore, the cost is least when the cost of one pier is equal to the cost of the main girders of one span, erected.

## Alternative Formulation
Sir Guilford Molesworth provides a less exact but convenient form for determining the economic span. In his formulation, if $G$ is the cost of the superstructure of a 100-ft. span erected and $P$ is the cost of one pier including its protection, the economic span ($l$) is calculated as:
$l = 100\sqrt{P}/\sqrt{G}$

## Sources
Compiled from: britannica11 vol03a brequigny to bulgaria
---
*Written by the AI Librarian strictly from the public-domain books of the archive. Topic memory: data/written-topics.json*
