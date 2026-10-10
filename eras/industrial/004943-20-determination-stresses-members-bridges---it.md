# Determination of Stresses in the Members of Bridges

The determination of stresses in bridge members is a fundamental aspect of structural engineering, ensuring that the loads carried by a structure do not exceed limits found by experience to be safe. In modern metal bridges, every member is designed with a definite function and is subjected to a calculated straining action. While the development of theory has diminished the margin of uncertainty and the need for empirical allowances, the economy of material remains critical, especially as increasing spans cause the dead weight of the superstructure to become a larger fraction of the total load.

## Principles of Stress Calculation
For beam girder or truss bridges, the primary focus is the determination of stresses in the main girders. These girders consist of a vertical web and an upper and lower flange (also referred to as booms or chords). For practical calculation, the web is considered to resist all vertical forces and equal horizontal shearing forces (in the case of a plate web), while the booms or chords are viewed as carrying exclusively horizontal tension and compression.

To determine the stresses, engineers consider vertical loading forces. Horizontal forces resulting from wind pressure are treated separately and managed via a horizontal system of bracing. The calculation involves determining the reactions at the abutments and the total shear and bending moment at any given section. For a beam with loads $W_1, W_2, ... W_n$, the reaction at the right abutment ($R_2$) is calculated as $W_1x_1/l+W_2x_2/l+...$, and the reaction at the left abutment ($R_1$) is the total load minus $R_2$. The bending moment ($M$) at a section is determined by the reaction $R_1$ multiplied by its distance from the section, minus the sum of the loads to the left of that section multiplied by their respective distances from it.

Additionally, J. Clerk Maxwell's concept of reciprocal figures provides a method for computing stresses in a frame. Two plane figures are reciprocal if they contain an equal number of lines where corresponding lines are parallel, and lines converging to a point in one figure form a closed polygon in the other. If a frame and its external forces are represented by one figure, the reciprocal figure represents the direction and magnitude of the forces between the joints, and thus the stress on each member.

## Permitted Stress Limits and Safety
Historically, engineers operated under the convenient belief that a total dead and live load stress on an iron structure not exceeding 5 tons per sq. in. provided ample safety. However, this simple rule is no longer sufficient. In 1885, Sir B. Baker described the state of opinion regarding safe stress limits as "chaotic," noting significant variances in the strength of existing bridges. He observed that a bridge acceptable to the English Board of Trade might require strengthening by 5% to 60% to be accepted by the German government or leading American railway companies.

Baker also highlighted the danger of repeated stress; he noted that bridges safely carrying twenty trains a day could fail quickly if subjected to twenty trains an hour, a fact he discovered through the fracture of girders during a five-minute train service.

## Working Stress Examples
English bridge-builders are often constrained by Board of Trade rules and do not universally adopt Wöhler's law. Various limits have been adopted for different structures:

*   **Dufferin Bridge (Steel):** Working stress was 6.5 tons per sq. in. for diagonals and bottom booms, 6.0 tons for top booms, and 5.0 tons for long compression members and verticals.
*   **Stanley Bridge (Brisbane):** Limits included 7.0 tons per sq. in. for tension booms, 6.5 tons for compression booms, diagonal ties, and cross and rail girders, 8.0 tons for wind bracing, and 5.0 tons for vertical struts.
*   **New Tay Bridge:** The general limit is 5 tons per sq. in., reducing to 4 tons per sq. in. for members where stress changes sign.
*   **Forth Bridge:** Limits varied based on frequency of stress change: 5.0 tons per sq. in. for frequent variation from 0 to maximum, 5.6 tons for rare variation, and between 3.3 and 5 tons for frequent or infrequent alternations of tension and thrust.

Regarding rivets, the shearing area in tension members was set at 1½ times the useful section of the plate in tension, while for compression members in butt-joints, it was half the useful section of the plate in compression.

## Fatigue and Impact Allowances
There is ongoing discussion regarding whether an additional allowance for impact should be made if the Weyrauch method is used to account for fatigue. Because Wöhler's experiments did not include impact, some argue for adding an impact allowance to the fatigue allowance, though this results in bridge sections larger than experience suggests are necessary. Some engineers reject fatigue allowances entirely, designing for total dead and live loads plus a large empirical allowance for impact.

Another perspective suggests that because the maximum live load ($f_{max.}$) used in Wöhler's law is not the usual load but one that occurs at long intervals, the fatigue allowance already covers the ordinary effects of impact. Alternatively, purely empirical impact allowances have been proposed: 20% of live load stresses for floor stringers, 15% for floor cross girders, 10% for 40-ft. main girder spans, and 5% for 100-ft. main girder spans.

## Load Types and Bridge Systems
The dead load of a bridge includes the weight of wind-bracing, flooring, and main girders. In railway bridges, sleepers and rails weigh 0.2 to 0.25 tons per ft. run per line, while rail and cross girders weigh 0.15 to 0.2 tons. Footways add approximately 0.4 ton per ft. run.

Different structural systems manage these stresses differently. The cantilever system, utilized in the Forth bridge and the Lansdowne bridge (where back guys are the most strained part, provided for at 1200 tons), allows for spans greater than independent girders. Cantilevers can be built from piers without temporary scaffolding, avoiding the interruption of navigation. In the Niagara Falls and Clifton steel arch, a two-hinged parabolic braced rib arch was used; the engineer employed specific expedients to annul bending action and excess compression in the upper member at the crown that typically occurs when a rib is erected on centering without initial stress.

## Sources
Compiled from: britannica11 vol03a brequigny to bulgaria
---
*Written by the AI Librarian strictly from the public-domain books of the archive. Topic memory: data/written-topics.json*
