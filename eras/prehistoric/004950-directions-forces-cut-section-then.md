# Analysis of Forces and Sections in Structural Engineering

In the study of braced structures and girders, the "Method of Sections" is employed to determine the stresses within individual components. This analytical approach allows engineers to calculate the internal forces acting on specific bars or flanges by examining a cross-section of the structure.

## The Method of Sections and Ritter's Method
For braced structures, Ritter's Method is a convenient application of the method of sections. This technique is used when a section of a girder can be taken such that it cuts only three bars. By taking moments, the stresses in these three bars—typically designated as C, S, and T—can be identified.

To calculate these forces, specific perpendicular distances are established from the joins of the bars:
*   **s** is the perpendicular from point O (the join of C and T) on the direction of force S.
*   **t** is the perpendicular from point A (the join of C and S) on the direction of force T.
*   **c** is the perpendicular from point B (the join of S and T) on the direction of force C.

Using the external forces to the left of the section (such as R, $W_1$, and $W_2$), the forces are calculated as follows:
*   $Ss = R_x - W_1(x+a) - W_2(x+2a)$
*   $Tt = R_{3a} - W_{12a} - W_{2a}$
*   $Cc = R_{2a} - W_{1a}$

More generally, if $M_1$, $M_2$, and $M_3$ represent the moments of the external forces to the left of points O, A, and B respectively, the relationships are expressed as $Ss = M_1$, $Tt = M_2$, and $Cc = M_3$. In a broader sense, for any bar with stress H and a perpendicular distance h from the join of the other two bars cut by the section, the formula $Hh = M$ applies, where M is the moment of the forces on one side of that join.

## Stress in Flanges and Webs
In girders where $A_t$ and $A_c$ represent the cross sections of the compression and tension flanges (or chords), and h is the distance between their mass centres, the total stress on each flange is $H_t = H_c = M/h$. The intensity of the stress for tension ($f_t$) and compression ($f_c$) is calculated as $f_t = M/A_{th}$ and $f_c = M/A_{ch}$, assuming these flanges resist all direct horizontal forces.

Regarding the plate web, if A is the area of the web in a vertical section, the intensity of shearing stress is $f_x = S/A$. This intensity remains the same on horizontal sections. In the case of a braced web, the vertical component of the stress in the web bars cut by the section must be equal to S.

## Distribution of Shearing Force and Bending Moment
The distribution of forces varies based on the load applied to a girder of span l supported at the ends.

### Fixed Load
When a fixed load W is carried at distance m from the right abutment, the reactions at the abutments are $R_1 = Wm/l$ and $R_2 = W(l-m)/l$. The shearing force distribution is represented by two rectangles, with shears on vertical sections to the left and right of the load being $R_1$ and $-R_2$. The bending moment increases uniformly from the abutments to the load, where it reaches $M = R_2m = R_1(l-m)$, forming a triangular distribution.

### Uniform Load
For a girder carrying a uniform load w per foot run, the total load is $wl$ and the reactions at the abutments are $R_1 = R_2 = ½wl$. In this scenario, the distribution of shear on vertical sections is represented by the ordinates of a sloping line. The greatest bending moment occurs at the centre ($M_c = 1/8wl^2$). At any point x from the abutment, the bending moment is $M = ½wx(l-x)$, which follows the equation of a parabola.

## Design for Dead and Equivalent Loads
In bridge design, specific equations are used to determine the uniform equivalent load ($w_e$). For a centre section, the moment is $M_c = ½w_ec^2$, and for a section at quarter span, the moment is $M_a = 3/8w_ec^2$. Bridges are designed for direct stresses based on bending moments resulting from both a uniform dead load and this uniform equivalent load.

## Sources
Compiled from: britannica11 vol03a brequigny to bulgaria
---
*Written by the AI Librarian strictly from the public-domain books of the archive. Topic memory: data/written-topics.json*
