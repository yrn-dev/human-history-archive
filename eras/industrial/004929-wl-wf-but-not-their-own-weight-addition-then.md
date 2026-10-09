# Bridge Load and Girder Weight Calculations

The determination of bridge loads and the subsequent calculation of girder weights involve the analysis of live loads, dead loads, and empirical allowances for impact stresses.

## Load Classifications and Impact Stresses
In bridge engineering, loads are categorized into live and dead loads. Live load stresses are subject to empirical allowances for impact stresses, which are added to the total. These allowances vary based on the component:
*   **Floor stringers:** 20% of live load stresses.
*   **Floor cross girders:** 15% of live load stresses.
*   **Main girders:** 10% for spans of 40 feet, and 5% for spans of 100 feet.

## Dead Load Components
The dead load is comprised of the weight of wind-bracing, flooring, and main girders. While generally considered to be uniformly distributed, the distribution of weight in main girders must be calculated and accounted for in large spans.

The weight of flooring depends on the bridge type. For railway bridges, the weight of rails and sleepers is estimated at 0.2 to 0.25 tons per foot run for each line of way, while cross girders and rail girders weigh between 0.15 and 0.2 tons. If a footway is included, an additional allowance of approximately 0.4 ton per foot run is made.

## Calculating Main Girder Weight
The weight of main girders increases as the span increases. There is a limiting span for any bridge type beyond which the dead load stresses exceed the assigned limit of working stress.

To calculate the weight of main girders ($W_g$), engineers consider the total live load ($W_l$) and the total flooring load ($W_f$) on a bridge of span $l$, both treated as uniform per foot run. If $k(W_l+W_f)$ represents the weight of main girders designed to carry the live and flooring loads—but not their own weight—then the weight of main girders required to carry $W_l+W_f$ and their own weight is expressed as:
$W_g = (W_l+W_f)(k+k^2+k^3 ...)$ or $W_g = (W_l+W_f)k/(1-k)$.

In practice, $k(W_l+W_f)$ is determined via a provisional design where the weight $W_g$ is neglected. The final bridge members must then have sections greater than those in the provisional design by the ratio $k/(1-k)$.

## Empirical and Rational Formulas
Waddell provides empirical relations for girder weights per foot run ($w_1, w_2$) for a live load $p$ and spans $l_1, l_2$:
$w_2/w_1 = ½ [l_2/l_1+(l_2/l_1)^2]$.

When live loads differ ($p$ and $p'$), the relations are:
*   $w_2'/w_2 = 1/5(1+4p'/p)$
*   $w_2'/w_1 = 1/10[l_2/l_1+(l_2/l_1)^2](1+4p'/p)$

Additionally, a partially rational approximate formula developed by Unwin (1869) defines the weight of main girders per foot run ($w_3$) using the following variables:
*   $w_1$: total live load per foot run of girder (tons).
*   $w_2$: weight of platform per foot run (tons).
*   $l$: span (ft).
*   $s$: average stress on gross section of metal (tons per sq. in.).
*   $d$: depth of girder at centre (ft).
*   $r$: ratio of span to depth ($l/d$).
*   $C$: a constant for the girder type.

The formula is expressed as $w_3 = (w_1+w_2)l^2/(Cds-l_2)$ or $w_3 = (w_1+w_2)lr/(Cs-lr)$.

## Sources
Compiled from: britannica11 vol03a brequigny to bulgaria
---
*Written by the AI Librarian strictly from the public-domain books of the archive. Topic memory: data/written-topics.json*
