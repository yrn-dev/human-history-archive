# The Method of J.J. Weyrauch and W. Launhardt

The method developed by J.J. Weyrauch and W. Launhardt is a system used extensively in the design of bridges. This approach is based on an empirical expression derived from Wöhler's law.

## Fundamental Concepts and Definitions
The method relies on three specific types of breaking strength to determine the limits of a bar's endurance:

*   **Statical Breaking Strength ($t$):** This is the breaking load divided by the original area of the section for a bar that is loaded once gradually until it fractures.
*   **Primitive Strength ($u$):** This refers to the breaking strength of a bar that is loaded and unloaded an indefinitely great number of times, with the stress alternating between $u$ and 0.
*   **Vibration Strength ($s$):** This is the breaking strength of a bar subjected to an indefinitely great number of repetitions of stresses that are equal and opposite in sign (tension and thrust), ranging alternately from $s$ to $-s$.

Values for $t$, $u$, and $s$ for various materials have been provided by the experiments of Bauschinger and Wöhler.

## Application of Wöhler's Law
According to Wöhler's law, if a bar is subjected to alternations of stress with a range ($\Delta$) defined as $f_{max.} - f_{min.}$, the bar will ultimately break if $f_{max.} = F\Delta$, where $F$ represents an unknown function.

Launhardt and Weyrauch provided approximate values for $F$ based on the nature of the stresses:
*   **Stresses of the same kind:** Launhardt found that $F = (t-u)/(t-f_{max.})$.
*   **Stresses of different kinds:** Weyrauch found that $F = (u-s)/(2u-s-f_{max.})$.

By utilizing these values for $F$ and solving for $f_{max.}$, the breaking stress for a bar subjected to varying stress repetitions can be determined. If $\phi$ is used to represent $f_{max.}/f_{min.}$ (where $\phi$ is positive for stresses of the same sign and negative for opposite signs), the formulas are:
*   **Stresses of same sign:** $f_{max.} = u(1+(t-u)\phi/u)$
*   **Stresses of opposite sign:** $f_{max.} = u(1+(u-s)\phi/u)$

## Calculation of Working Stress
To determine the working stress ($f$), the $f_{max.}$ value is divided by a factor of safety. Using a factor of safety of 3, and applying the results from Bauschinger (for steel) and Wöhler (for iron), the following equations for tension or thrust are derived:
*   **Iron:** $f = 4.4 (1+½\phi)$
*   **Steel:** $f = 5.87 (1+½\phi)$

In these instances, $\phi$ is assigned a positive or negative value depending on the specific case. For shearing stresses, the working stress is calculated as 0.8 of the value used for tension.

## Considerations for Impact and Fatigue
There is ongoing professional discussion regarding whether an additional allowance for impact should be made if the Weyrauch method is already used to account for fatigue. Because Wöhler's original experiments did not include impact, it might seem rational to add an impact allowance to the fatigue allowance. However, doing so results in bridge sections that are larger than experience indicates is necessary.

Some engineers address this by arguing that Wöhler's results are not applicable to bridge work. These practitioners reject the allowance for fatigue (the effect of repetition) and instead design bridge members based on the total live and dead load, adding a large impact allowance based on a purely empirical rule.

Conversely, when applying Wöhler's law, $f_{max.}$ is determined based on the maximum possible live load. While this load must be provided for, it is not the usual live load the bridge experiences. Consequently, the range of stress ($f_{max.} - f_{min.}$) used to deduce working stress is not the ordinary range repeated an infinite number of times, but one that occurs only at comparatively long intervals. Because of this, it appears probable in practice that the fatigue allowance provided in the Launhardt and Weyrauch formulas is sufficient to cover ordinary effects of impact as well.

## Sources
Compiled from: britannica11 vol03a brequigny to bulgaria
---
*Written by the AI Librarian strictly from the public-domain books of the archive. Topic memory: data/written-topics.json*
