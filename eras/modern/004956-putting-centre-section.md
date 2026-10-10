# Putting x = 0, for the centre section

## Engineering Calculations for Bridge Girders
In the design of bridge girders, specific mathematical equations are used to determine bending moments and stresses. For a girder where $M = ½w_e(c-x)(c+x)$, the value for the centre section is found by putting $x = 0$, resulting in $M_c = ½w_ec^2$. Additionally, for a section at quarter span, putting $x = ½c$ results in $M_a = 3/8w_ec^2$. These equations allow for the determination of a value for $w_e$, which is then used to design the bridge regarding direct stresses for bending moments caused by a uniform equivalent load $w_e$ and a uniform dead load.

## Structural Components and Stress Distribution
Bridge girders typically consist of a horizontal girder subjected almost exclusively to vertical loading forces. To balance external forces, material is primarily arranged into a bottom flange or chord (subjected to tension) and a top flange, boom, or chord (subjected to compression). These flanges are connected by a vertical web, which can be a system of bracing bars or a solid plate, creating a structure that is virtually an I section.

The distribution of stress varies across the structure:
*   **Flanges:** These resist horizontal tension and compression distributed practically uniformly across their cross sections. The horizontal stresses are greatest at the centre of a span.
*   **Web:** The web resists forces equivalent to shear on horizontal and vertical planes. Stresses in the web are greatest at the ends of the span. In cases where girders have curved chords, the stresses in the web are diminished.

## Method of Sections and Stress Intensity
The "Method of Sections" (specifically Ritter's Method) is used for braced structures. When a girder section is taken cutting only three bars, the stresses in those bars—denoted as $C$, $S$, and $T$—can be found by taking moments. For example, if $m\ n$ cuts three bars, the external forces to the left of the section are $W_1$, $W_2$, and $R$. Moments are taken about specific points:
*   About point $O$ (the join of $C$ and $T$ on the direction of $S$): $R_x-W_1(x+a)-W_2(x+2a) = Ss$.
*   About point $A$ (the join of $C$ and $S$ on the direction of $T$): $R3a-W_12a-W_2a = Tt$.
*   About point $B$ (the join of $S$ and $T$ on the direction of $C$): $R2a-W_1a = Cc$.

Regarding stress intensity, if $h$ is the distance between the mass centres of the compression and tension flanges ($A_c$ and $A_t$), and they resist all direct horizontal forces, the total stress on each flange is $H_t = H_c = M/h$. The intensity of compression is $f_c = M/A_{ch}$ and tension is $f_t = M/A_{th}$. For a vertical section with plate web area $A$, the intensity of shearing stress is $f_x = S/A$.

## Bending Moment and Shearing Force
For a girder of span $l$ supported at the ends:
*   **Fixed Load:** If a fixed load $W$ is carried at $m$ from the right abutment, reactions are $R_1 = Wm/l$ and $R_2 = W(l-m)/l$. The bending moment increases uniformly from the abutments to the load, where $M = R_2m = R_1(l-m)$.
*   **Uniform Load:** If the girder carries a uniform load $w$ per foot run, the total load is $wl$ and reactions are $R_1 = R_2 = ½wl$. The bending moment at any point $x$ from the abutment is $M = ½wx(l-x)$, which follows a parabola. The greatest bending moment occurs at the centre, where $M_c = 1/8wl^2$.

## Sources
Compiled from: britannica11 vol03a brequigny to bulgaria
---
*Written by the AI Librarian strictly from the public-domain books of the archive. Topic memory: data/written-topics.json*
