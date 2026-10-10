# Bending Moment Due to Uniform Loads

In the engineering of girders and bridges, the bending moment is a critical factor in determining the necessary strength of the structure. When a girder is subjected to a uniform load per foot run, the resulting bending moments follow specific mathematical patterns, typically forming a parabola.

## Uniform Loads on Fixed Girders
For a girder of span $l$ supported at its ends and carrying a fixed uniform load $w$ per foot run, the total load is calculated as $wl$. The reactions at the abutments are equal, with $R_1 = R_2 = \frac{1}{2}wl$. Under these conditions, the distribution of shear on vertical sections is represented by the ordinates of a sloping line.

The greatest bending moment occurs at the center of the span, denoted as $M_c$, and is equal to $\frac{1}{8}wl^2$. At any point $x$ measured from the abutment, the bending moment is expressed by the equation $M = \frac{1}{2}wx(l-x)$, which describes a parabola.

## Travelling Uniform Loads
When a uniform travelling live load $w$ per foot run advances across a girder from the left abutment, the bending moments change as the load moves. If the center of the load is at a distance $x$ from the left abutment, the reaction at the right abutment (B) is $\frac{2wx^2}{l}$. The bending moment at any section C, located at distance $m$ from the left abutment, is $\frac{2wx^2(l-m)}{l}$. This value increases as $x$ increases until the entire span is covered. Consequently, for uniform travelling loads, the bending moments reach their maximum when the loading of the span is complete.

## Equivalent Uniform Loads for Bridge Design
In the design of bridges, engineers often deal with concentrated loads, such as railway rolling stock. Because the precise magnitude and distribution of these loads vary, designers may assume a set of loads likely to produce more severe straining than probable actual loads. 

For most bridges (excluding very short ones or those with very unequal loads), a parabola can be found that encompasses the curve of maximum moments. This parabola represents the curve of maximum moments for a travelling load that is uniform per foot run. The load per foot run that produces these maximum moments is termed the equivalent uniform load, denoted as $w_e$.

To find $w_e$ for practical design purposes, experience indicates that a parabola agreeing closely with the curve of maximum moments can be found by ensuring it has the same ordinate at either the center of the span or at one-quarter span.

## Bending Moments in Girders of Span 2c
For a girder with a span of $2c$, the bending moment $M$ at a section located at distance $x$ from the center, due to a uniform load $w_e$ per foot run, is calculated as:
$M = \frac{1}{2}w_e(c-x)(c+x)$

Based on this equation, specific moments can be determined:
*   **At the center section ($x = 0$):** The moment $M_c = \frac{1}{2}w_ec^2$.
*   **At the quarter span section ($x = \frac{1}{2}c$):** The moment $M_a = \frac{3}{8}w_ec^2$.

These equations allow for the calculation of $w_e$, which is then used to design the bridge for direct stresses, accounting for both the uniform dead load and the uniform equivalent load $w_e$.

## Equivalent Loads for Locomotives
Research by Farr involved drawing bending moment diagrams for forty different heavy locomotives across various spans to determine the uniform load that would produce a bending moment at every point as great as the actual wheel loads. Examples of these equivalent uniform loads per foot run for each track include:
*   **5.0 ft span:** 7.6 tons
*   **10.0 ft span:** 4.85 tons
*   **20.0 ft span:** 3.20 tons
*   **30.0 ft span:** 2.63 tons
*   **50.0 ft span:** 2.24 tons
*   **100.0 ft span:** 1.97 tons

## Sources
Compiled from: britannica11 vol03a brequigny to bulgaria
---
*Written by the AI Librarian strictly from the public-domain books of the archive. Topic memory: data/written-topics.json*
