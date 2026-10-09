# Permitted Stresses in Engineering

The determination of permitted stresses in structural engineering has evolved from simple, generalized rules to complex calculations based on material properties, the nature of the load, and the effects of repeated stress.

## Evolution of Stress Standards
For a significant period, engineers operated under the convenient assumption that safety was secured if the total stress from dead and live loads on any section of an iron structure did not exceed 5 tons per square inch. However, this simple rule eventually became insufficient for modern design. By 1885, Sir B. Baker described the state of opinion regarding safe stress limits as "chaotic," noting that the strength of existing bridges varied so significantly that the differences were apparent to the educated eye without calculation. 

While engineers reached an agreement on the principles for estimating the magnitude of stresses on structural members, they remained divided on how to proportion those members to resist such stresses. This lack of consensus resulted in significant discrepancies in international standards; for example, a bridge acceptable to the English Board of Trade might require strengthening by 5% in some areas and 60% in others to be accepted by the German government or leading American railway companies.

## The Impact of Repetition and Fatigue
Practical experience revealed that while 5 tons per square inch for iron, or 6½ tons per square inch for steel, was safe for long bridges with a large ratio of dead to live load, it was unsafe for short bridges where stresses are primarily caused by live loads and the bridge's own weight is small. 

Experiments conducted by A. Wöhler, and later repeated by Johann Bauschinger and Sir B. Baker, demonstrated that the breaking stress of a bar is not a fixed quantity. Instead, it depends on the range of variation of stress if that variation is repeated a very large number of times. This is termed the "repetition of stress." Sir B. Baker observed that hundreds of bridges carrying twenty trains a day safely would break down quickly if subjected to twenty trains an hour, a fact highlighted by the fracture of girders of ordinary strength during a five-minute train service.

To calculate these limits, engineers use the statical breaking strength (K), which is the strength when a bar is loaded once gradually to breaking. The breaking strength when subjected to alternating stresses (k_{max.}) is determined by the range of stress ([Delta]), which is the difference between maximum and minimum stresses (k_{max.} - k_{min.}) if they are of the same kind, or the sum (k_{max.} + k_{min.}) if they are of opposite kinds. Wöhler's results follow the rule: k_{max.} = ½[Delta]+[root](K²-n[Delta]K).

## Live Loads and Impact Stresses
In certain regions, such as Austria, official regulations mandate specific live loads per foot run and per track based on the span of the railway bridge. For instance, a span of 1 metre (3.3 ft) requires a live load of 6.1 tons per foot run, while a span of 30 metres (98.4 ft) requires 1.2 tons per foot run. Some suggest that designing for a typical heavy locomotive would be safer and simpler than assuming a uniform rolling load, particularly for shearing forces and flooring girders.

Stresses are further complicated by "impact." When a vertical load is imposed suddenly without velocity, deformation and stress are momentarily doubled compared to a load at rest. In actual bridge use, stresses are increased by:
* Deflections that increase with speed.
* Centrifugal and lurching actions caused by rails that are not perfectly smooth or straight.
* Unbalanced vertical moving parts of the engine.
* Shocks caused by inequalities of level at rail ends.

These impact stresses are more pronounced on short main girders than long ones, and more significant on flooring girders than main ones. E.H. Stone found that the increment of deflection due to impact depends on the ratio of dead to live load.

## Fatigue and Impact Allowances
There is ongoing professional discussion regarding whether an additional allowance for impact should be made if the Weyrauch method is already used to allow for fatigue. Adding both can result in bridge sections larger than experience suggests is necessary. Some engineers reject the allowance for fatigue entirely, instead designing for total dead and live loads plus a large empirical allowance for impact. However, because the maximum possible live load used in Wöhler's law is not the usual load a bridge faces, it is probable that fatigue allowances sufficiently cover ordinary impact effects.

## Theoretical Application and Verification
The application of stress theory was exemplified by the Boyne bridge in Ireland (1854-1855). This bridge featured lattice girders continuous over three spans, with a centre span of 264 ft. Engineers tested their calculations by removing rivets at the calculated points of contrary flexure in the top boom. By lowering the girder end by one inch and opening the joint by 1/32 in, they proved there was no stress in the boom where the bending moment changes sign, verifying the theoretical design.

## Sources
Compiled from: britannica11 vol03a brequigny to bulgaria
---
*Written by the AI Librarian strictly from the public-domain books of the archive. Topic memory: data/written-topics.json*
