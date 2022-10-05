---
title: Insulation
weight: 2
---


# Insulation

Insulation is a method for preventing the flow of electricity to areas neighboring your traces. Some soft sensor and actuator structures rely on traces being insulated from one and other, others don't. In some cases, you might also find that your materials already come insulated. In others, you need to provide insulation yourself. You can test if your material is insulated or not by connecting a multimeter (using the continuity setting) across a length of conductive string and seeing and checking for a connection. In some other cases, you may want to insulate your entire circuit or just one trace from another. Below we list a few common methods for insulating: 

### Coatings

the most frequent way that materials are insulated when you purchase them from suppliers is with a a coating. For instance, [magnet wire](../materials/metallic-fibers.md#copper) often comes with a thin enamel coating. In order to connect directly to the metal wire, you have to burn \(with a lighter\) or use sandpaper to scratch the enamel. In other wires, the coating is more easily spotted as a thicker and/or colored flexible silicone. These coatings can affect the performance of your circuit. For instance, in tests of heating wire, we found that even a thin layer of enamel coating limited the heat transfer between the conductive element and materials.

### Covering/Layering

Some wires you source will come entirely wrapped in fiber to provide coding, such as cotton covered wires. These are essentially [core spun](/docs/structure/core-spun-yarn.md) yarns with conductive cores and non-conductive/insulating sheaths. In other cases, you may cover your entire circuit in an insulating materials \(like felt\) so you can bend it without the fear of crossing traces. 

### Woven Spacing

A second technique is to space your uninsulated traces such that they will not touch. This works well when your circuit will lay flat or will not fold upon itself unintentionally. Tests can help you determine how much spacing you need between traces to ensure they do not contact. In weaving, the amount of spacing or pics you need between traces depends on the structure. We tested tabby, twill, in satins in several lengths to test to see if the wires would short across the length of the fabric. Our results show that tabby will not short even if it is entirely woven with conductive yarn: 

![](/tabby_microscope.png)


This is because tabby has the most interlacements, meaning that each warp and weft is held the most firmly in its place and that the interlacements between every yarn push the successive weft rows away from one another. 

Twill and Satin show similar qualties at rest, but when you pull on them, then the short across the length. 

In twills, the samples short when pulled in diagonoal corners that match the direction of the twill:

![](/twill_weft_conductive_experiments.png)

In satins, the samples short when pulled in EITHER diagonoal corner:

![](/satin_weft_conductive_experiments.png)

These observations reflect the structural nature of each swatch as twills have interlacements oriented more stongly along a diagonal, and satins are more structually balanced, with interlacements evenly distributed through the structure. Tabby, being all interlacements, keeps the sucessive traces most insulated in our cases and while this may depend on the ratio of warp ends per inch to pics per inch, we think it would likely hold in most cases, especially when the yarn densities in both directions are balanced.


### Beads

beads can be useful form of adding insulation around regions of an uninsulated conductive yarn, particularly for applications where you need movement and flexibility. The bead acts as a sheath protecting that section from yarn from becoming touched by another. 

