# PCB Design Palette
## A reference tool for creating PCB artwork.

Normally, printed circuit boards are fairly boring and technical, albeit ubiquitous and indispensable, bits of technology used nearly everywhere in the modern world. However, from PCB conference badges, to decorative development boards, to PCB art pieces, there are a surprising number of ways to use PCBs for aesthetic purposes as well. Even when PCBs are designed with no consideration at all for aesthetics, they have a kind of techie visual appeal, with thin traces arranged in integrate patters and components arranged and soldered with (literally) robotic precision. Despite their being about as far from the natural world as it is possible to get, PCBs can have an almost growth-like look, like some kind of slime mold working to connect food sources in the most efficient way possible.

Anyway, when it comes to designing decorative PCBs, it is useful to have a reference for all the possible ways that the different layers of a PCB design can be used to create different colors and effects. This is like a painter with a pallet from which they are able to quickly incorporate all kinds of colors into their artwork.

The **PCB Design Palette** includes five sections, some of which have two parts, that each have a different combination of layers in the PCB design. These combinations produce different colors and effects on the finished PCB:

### “Standard Layers” Section
The top section on the PCB uses a set of layers that PCB designs would typically be used in most production designs. The section has a series of traces, vias, an SMD pad, and some silkscreen elements.

### “GND Plane/Soldermask” Section
The next section also uses a set of layers that is common on PCB designs. The set of design elements is the same as the “Standard Layers” section but this time the section has a ground fill covering the entire negative area of the section.

### “Keepout | GND Plane” Section
The third section is divided into a left and a right half. Both halves of the section are covered by rectangle on the *keepout* layer.  The right half of this section also has a ground plane, but the left section does not.

### “tStop | GND Plane” Section
The fourth section is also divided into two halves that are similar to the layer above. Both halves of the section are covered by a rectangle on the *tStop* layer. The right half of the section has a ground plane and the left section does not.

### “Restrict + Keepout” Section
The last section has only one part. The section has trances, an SMD pad, and vias that are covered by rectangles on the *restrict* and *keepout* layers.
