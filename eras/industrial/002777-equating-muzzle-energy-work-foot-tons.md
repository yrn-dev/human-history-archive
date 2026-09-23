# Equating Muzzle-Energy and Work in Foot-Tons

In the study of interior ballistics, the relationship between the energy of a shot at the muzzle and the work performed by powder-gas is analyzed using indicator diagrams. These diagrams graphically represent the relation between the pressure and volume of the powder-gas via a curve. From these, curves for time, velocity, and energy can be derived.

## Calculation of Net Work and Kinetic Energy
The net work realized by the powder-gas as a shot advances is represented by the area of the indicator diagram after accounting for recoil and friction. This net work is equated to the kinetic energy ($e$) of the shot, measured in foot-tons. The formula for this energy is:

$e = \{w / 2240\} (1 + \{4k^2 / d^2\} \tan^2 [\delta]) \{v^2 / 2g\}$

In this equation, $d$ represents the diameter of the shot and $k$ is the axial radius of gyration. The term $4(k^2/d^2)\tan^2[\delta]$, where $[\delta]$ is the angle of the rifling, accounts for the fraction of energy due to the rotation of the shot. Because this factor is typically small—less than 1%—it is often ignored in subsequent calculations.

## Mean Effective Pressure and Work
The Mean Effective Pressure (M.E.P.), measured in tons per square inch, is represented by a height such that a rectangle formed by this height and the travel of the shot is equal to the area of the pressure-volume curve. 

The work realized in inch-tons is calculated by multiplying the M.E.P. by the cross-section of the bore ($1/4[\pi]d^2$) and then by the length of the travel ($l$) of the shot up the bore. This work is equal to the M.E.P. multiplied by the volume of the rifled part of the bore ($B - C$), where $B$ is the total volume of the bore and $C$ is the volume of the powder-chamber.

## Equating Muzzle-Energy and Work
To equate the muzzle-energy ($E$) and the work in foot-tons, the following relationship is used:

$E = w/2240 V^2/2g = \{B - C\} / 12 \times \text{M.E.P.}$

From this, the M.E.P. can be determined as:

$\text{M.E.P.} = w/2240 V^2/2g \times 12/\{B - C\}$

For example, in a 6-inch gun with a length ($L$) of 216 inches and a rifled volume ($B - C$) of 6100 cubic inches, the M.E.P. is approximately 6.4 tons per square inch. It is noted that maximum pressure may exceed this mean pressure in a ratio of 2 or 3 to 1.

## Expansion and Energy Loss
When calculating the energy acquired by a shot, an average pressure can be used. For instance, a shot advancing 3.225 feet under an average pressure of 8 tons per square inch acquires 730 foot-tons of energy. 

If the combustion of the charge (such as cordite) is complete at a certain stage, the subsequent expansion is assumed to follow an adiabatic law where pressure varies inversely as the $m^{th}$ power of the volume (with $m = 1.2$ being a good average for cordite). The work done in expanding from a volume $b$ to a volume $B$ is expressed as:

$(9) \text{ work} = pb/\{m - 1\}[1 - (b/B)^{m-1}]$

In practical applications, a "factor of effect" (such as $f = 0.9$) is used to account for energy lost to friction in the bore, which may be approximately 10% of the work.

## Gravimetric Volume and Work
The work ($E$) in foot-tons realized by the expansion of 1 lb of powder can be inferred from the gravimetric volume. If the average pressure is $p$ tons per square inch and the gravimetric volume changes by $\Delta v$, the work done is $27.73p\Delta v$ inch-tons, or:

$\Delta E = 2.31 p\Delta v \text{ foot-tons}$

## Sources
Compiled from: britannica11 vol02b baconthorpe to bankruptcy
---
*Written by the AI Librarian strictly from the public-domain books of the archive. Topic memory: data/written-topics.json*
