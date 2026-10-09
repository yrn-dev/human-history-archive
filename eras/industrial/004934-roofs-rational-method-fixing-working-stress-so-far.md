# Roofs and Structural Stress in Engineering

The design and construction of structural elements, including those used in roofs and bridges, rely on the calculation of working stress to ensure safety and stability. A primary concern in these calculations is the effect of repeated loading, often referred to as "fatigue," and the impact of live loads compared to dead loads.

## Working Stress and Fatigue
In the study of iron and steel, the breaking stress of a bar is affected by the repetition of loading. The term "fatigue" is used to describe the phenomenon where the breaking stress diminishes as the range of variation in loading increases. For a bar under a statical load where the range of stress is nil, the maximum stress ($k_{max.}$) is equal to the statical breaking stress ($K$). However, if a bar is alternately loaded and then the load is removed, $k_{max.}$ becomes $0.6 K$. In cases where a bar is subjected to equal amounts of alternate tension and compression, $k_{max.}$ is $0.33 K$. 

The safe working stress is determined by dividing $k_{max.}$ by a factor of safety. For ductile iron or mild steel, a constant $n$ (varying from 1.3 to 2) may be taken as 1.5.

## Methods of Fixing Working Stress
As early as 1869, Unwin suggested in *Wrought Iron Bridges and Roofs* that a rational method for fixing working stress should depend on the ratio of live load to dead load. Specifically, the factor of safety for live load stresses should be double that for dead load stresses.

Other engineers utilize Wöhler's law to determine working stress. Under this approach, the maximum stress ($f_{max.}$) is found based on the maximum possible live load. While this load may not be the usual load the structure is subjected to, it must be provided for. Because the range of stress deduced from this maximum is not the ordinary range repeated an infinite number of times, it is generally considered that the allowance for fatigue is sufficient to cover the ordinary effects of impact.

Some engineers reject the allowance for fatigue entirely, instead designing members for the total dead and live load plus a large allowance for impact based on empirical rules.

## Impact and Live Loads
Impact occurs when a vertical load is imposed suddenly. If imposed without velocity, the deformation and stress are momentarily double those of a load at rest. In practical bridge applications, stresses due to live loads are greater than those of a resting load due to several factors:
*   Centrifugal and lurching actions caused by rails that are not perfectly smooth or straight.
*   Shocks resulting from inequalities of level at rail ends.
*   Rapidly changing forces from unbalanced moving parts of an engine.

These impact stresses are more pronounced on short main girders than long ones, and more significant on flooring girders than on main girders. E.H. Stone found that the increment of deflection due to impact depends on the ratio of dead to live load.

## Practical Applications and Limits
Different projects adopt various limits for working stress. For example:
*   **Dufferin Bridge (steel):** Working stress was 6.5 tons per sq. in. in diagonals and bottom booms, 6.0 tons in top booms, and 5.0 tons in long compression members and verticals.
*   **Stanley Bridge (Brisbane):** Limits ranged from 5.0 tons per sq. in. in vertical struts to 8.0 tons in wind bracing.
*   **New Tay Bridge:** Generally 5 tons per sq. in., reducing to 4 tons per sq. in. for members where stress changes sign.
*   **Forth Bridge:** Limits were 5.0 tons per sq. in. for frequent stress variation (0 to maximum) and 5.6 tons per sq. in. for rare variation. For frequent alternations of thrust and tension, the limit was 3.3 tons per sq. in., rising to 5 tons per sq. in. if alternations were infrequent.

Regarding rivets, the shearing area in tension members was set at 1½ times the useful section of plate in tension, while for compression members in butt-joints, it was half the useful section of plate in compression.

## Girder Weight and Calculation
The weight of main girders ($W_g$) can be calculated based on the live load ($W_l$) and flooring weight ($W_f$) using the formula $W_g = (W_l+W_f)k/(1-k)$. 

Unwin provided a partially rational approximate formula for the weight of main girders ($w_3$):
$w_3 = (w_1+w_2)lr/(Cs-lr)$
In this formula, $w_1$ is the total live load per ft. run, $w_2$ is the weight of the platform per ft. run, $l$ is the span, $r$ is the ratio of span to depth ($l/d$), $s$ is the average stress on the gross section, and $C$ is a constant for the girder type.

## Sources
Compiled from: britannica11 vol03a brequigny to bulgaria, britannica11 vol14a ichthyology to independence, britannica11 vol05b carnegie to casus belli
---
*Written by the AI Librarian strictly from the public-domain books of the archive. Topic memory: data/written-topics.json*
