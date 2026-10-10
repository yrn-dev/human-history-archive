# Breaking Stress and Material Fatigue

The breaking stress of a bar is not a fixed quantity but is dependent upon the range of variation of stress to which the material is subjected, provided that variation is repeated a very large number of times. This phenomenon is often referred to as "fatigue," a term used to describe the process where the breaking stress under repeated loading diminishes as the range of variation increases.

## Statical and Dynamic Breaking Strength
In the study of material strength, several distinct types of breaking strength are defined:
*   **Statical Breaking Strength (K or t):** The breaking strength per unit of section when a bar is loaded once gradually until it fractures.
*   **Primitive Strength (u):** The breaking strength of a bar that is loaded and unloaded an indefinitely great number of times, with the stress varying alternately from $u$ to 0.
*   **Vibration Strength (s):** The breaking strength of a bar subjected to an indefinitely great number of repetitions of stresses that are equal and opposite in sign (tension and thrust), ranging alternately from $s$ to $-s$.

## Wöhler's Law and Range of Stress
Experiments conducted by A. Wöhler and repeated by Johann Bauschinger, Sir B. Baker, and others, established the relationship between breaking stress and the range of stress. The range of stress ($\Delta$) is defined as $k_{max} \pm k_{min}$. If the stresses are of the same kind, the range is $k_{max} - k_{min}$; if they are of opposite kinds, the range is $k_{max} + k_{min}$.

Wöhler's results align closely with the rule:
$k_{max} = \frac{1}{2}\Delta + \sqrt{K^2 - n\Delta K}$

In this equation, $n$ is a constant that varies between 1.3 and 2 depending on the quality of the steel or iron. For mild steel or ductile iron, $n$ may be taken as 1.5.

Specific cases of this rule include:
*   **Statical Load:** Where the range of stress is nil ($\Delta = 0$), $k_{max}$ equals the statical breaking stress ($K$).
*   **Alternating Load and Removal:** Where $\Delta = k_{max}$, the breaking strength $k_{max} = 0.6 K$.
*   **Equal Alternate Tension and Compression:** Where $\Delta = 2 f_{max}$, the breaking strength $k_{max} = 0.33 K$.

## Empirical Expressions for Bridge Design
The methods of W. Launhardt and J.J. Weyrauch provide empirical expressions for Wöhler's law used in bridge design. They utilize a function $F$ to determine the breaking stress ($f_{max}$) of a bar subjected to varying stress: $f_{max} = F\Delta$.

*   **Same-kind Stresses:** Launhardt found that $F = \frac{t-u}{t-f_{max}}$ approximately agreed with experimental data.
*   **Different-kind Stresses:** Weyrauch found that $F = \frac{u-s}{2u-s-f_{max}}$ was similarly approximate.

By solving for $f_{max}$ using $\phi$ (which is positive for stresses of the same sign and negative for opposite signs), the following formulas are derived:
*   **Stresses of same sign:** $f_{max} = u(1 + \frac{(t-u)\phi}{u})$
*   **Stresses of opposite sign:** $f_{max} = u(1 + \frac{(u-s)\phi}{u})$

## Working Stress and Safety Factors
The safe working stress ($f$) is determined by dividing the breaking stress ($k_{max}$ or $f_{max}$) by a factor of safety. Using a factor of safety of 3, the equations for tension or thrust are:
*   **Iron:** $f = 4.4(1 + \frac{1}{2}\phi)$
*   **Steel:** $f = 5.87(1 + \frac{1}{2}\phi)$

For shearing stresses, the working stress may be 0.8 of the value calculated for tension.

Practical engineering experience indicates that while 6½ tons per sq. in. for steel or 5 tons per sq. in. for iron is safe for long bridges with a large ratio of dead to live load, these values are not safe for short bridges where stresses are mainly due to live load and the bridge weight is small. Consequently, it has been suggested that a rational method for fixing working stress should make it depend on the ratio of live to dead load, ensuring the factor of safety for live load stresses is double that for dead load stresses.

## Sources
Compiled from: britannica11 vol03a brequigny to bulgaria
---
*Written by the AI Librarian strictly from the public-domain books of the archive. Topic memory: data/written-topics.json*
