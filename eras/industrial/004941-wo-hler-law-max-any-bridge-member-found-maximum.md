# Wöhler's Law and Bridge Member Stress

Wöhler's law describes the relationship between the breaking stress of a material and the range of stress variation to which it is subjected when that variation is repeated a very large number of times. These findings, which were repeated by others including Sir B. Baker and Johann Bauschinger, demonstrate that the breaking stress of a bar is not a fixed quantity but diminishes as the range of variation increases. This phenomenon is commonly referred to as "fatigue."

## Theoretical Principles of Wöhler's Law
The law distinguishes between different types of breaking strength. The statical breaking strength ($K$) is the breaking strength of a bar per unit of section when it is loaded once gradually until it breaks. When a bar is subjected to stresses varying alternately between a maximum ($k_{max.}$) and a minimum ($k_{min.}$) an indefinitely great number of times, the breaking strength is determined by the range of stress ($\Delta$). 

The range of stress is calculated as $k_{max.} - k_{min.}$ if the stresses are of the same kind (both tension or both thrust), and $k_{max.} + k_{min.}$ if they are of opposite kinds. Wöhler's results align with the rule:
$k_{max.} = ½\Delta + \sqrt{K^2 - n\Delta K}$

In this formula, $n$ is a constant that varies between 1.3 and 2 depending on the quality of the steel or iron; for mild steel or ductile iron, it is typically 1.5. Under these parameters, a bar that is alternately loaded and unloaded ($\Delta = k_{max.}$) has a $k_{max.}$ of $0.6K$. A bar subjected to equal amounts of alternate tension and compression ($\Delta = 2f_{max.}$) has a $k_{max.}$ of $0.33K$.

## Application to Bridge Design
In the context of bridge engineering, Wöhler's law is used to determine the safe working stress, which is found by dividing $k_{max.}$ by a factor of safety. When applying the law to a bridge member, $f_{max.}$ is determined based on the maximum possible live load. While this maximum load may not be the usual load the bridge is subjected to, it must be provided for because it occurs occasionally.

Because the range of stress ($f_{max.} - f_{min.}$) is derived from this maximum possible live load rather than the ordinary range of stress repeated an infinite number of times, the bridge is subjected to this specific range only at comparatively long intervals. Consequently, it appears probable that allowances for fatigue are sufficient to cover the ordinary effects of impact as well.

## The Weyrauch and Launhardt Method
The method developed by W. Launhardt and J.J. Weyrauch is based on an empirical expression of Wöhler's law. This method utilizes three specific strengths:
*   **Statical breaking strength ($t$):** The strength when loaded once gradually to fracture.
*   **Primitive strength ($u$):** The breaking strength when stress varies from $u$ to 0 alternately.
*   **Vibration strength ($s$):** The breaking strength when subjected to equal and opposite stresses ranging from $s$ to $-s$.

If a bar is subjected to a range of stress $\Delta = f_{max.} - f_{min.}$, the bar will ultimately break if $f_{max.} = F\Delta$. Launhardt found that for stresses of the same kind, $F = (t-u)/(t-f_{max.})$, while Weyrauch found that for stresses of different kinds, $F = (u-s)/(2u-s-f_{max.})$.

Using a factor of safety of 3, the working stress ($f$) for tension or thrust is calculated as:
*   **Iron:** $f = 4.4 (1 + ½\phi)$
*   **Steel:** $f = 5.87 (1 + ½\phi)$

In these equations, $\phi$ represents $f_{max.}/f_{min.}$, taking a positive value for stresses of the same sign and a negative value for opposite signs. For shearing stresses, the working stress is generally 0.8 of the value for tension.

## Engineering Perspectives and Variations
Not all engineers accept the guidance of Wöhler's law for bridge work. Some assert that the results are not applicable to bridges, rejecting the allowance for fatigue (the effect of repetition) entirely. Instead, these engineers design members for the total dead and live load and add a large allowance for impact based on empirical rules.

Different bridges exhibit varying limits of working stress. For example:
*   **Dufferin Bridge (steel):** Working stress was 6.5 tons per sq. in. in diagonals and bottom booms, 6.0 tons in top booms, and 5.0 tons in verticals.
*   **Stanley Bridge (Brisbane):** Limits ranged from 5.0 tons per sq. in. in vertical struts to 8.0 tons in wind bracing.
*   **New Tay Bridge:** The limit is generally 5 tons per sq. in., reducing to 4 tons per sq. in. for members where stress changes sign.
*   **Forth Bridge:** Limits were 5.0 tons per sq. in. for stresses varying from 0 to a maximum frequently, and 3.3 tons per sq. in. for frequent alternations of tension and thrust.

## Sources
Compiled from: britannica11 vol03a brequigny to bulgaria
---
*Written by the AI Librarian strictly from the public-domain books of the archive. Topic memory: data/written-topics.json*
