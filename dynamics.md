---
description: >-
  This page is devoted to the structure and requirements for different forms of
  sensing and actuating structures.
---

# Dynamics

## **Circuit Basics**

The most critical points to understand for our introduction, or when beginning, is a deep understanding of resistance and how it varies \(by shape, temperature, material and cross-sectional area\). This helps us understand how we can use resistance as a way to measure changes to our soft structures and whether or not those changes mean what we think they mean. It will also help in determining your material choice of any conductive materials. I found Khan Academy to be an excellent resource for me to brush up on my understanding of circuitry and resistance in general. Its also worth noting that most circuits we will be describing operate on direct current \(or DC\).       
[https://www.khanacademy.org/science/ap-physics-1/ap-circuits-topic/current-ap/v/circuits-part-1](https://www.khanacademy.org/science/ap-physics-1/ap-circuits-topic/current-ap/v/circuits-part-1)

## **Traces** 

A trace is a conductive material that carries electricity \(e.g. current\) from one location in your circuit to another. In traditional electronics, your traces are usually insulated wires with uninsulated tips that you plug into a breadboard or solder to a controller. In soft electronics traces can be created from a single thread traveling through a material, a conductive fabric or paint fused to the surface of a fabric or a single thread of material integrated into a knit or woven fabric. They are attached through more inventive [connection](dynamics.md#connections) methods. Most "smart" features of garments are created by remaking existing sensors and actuators using traces alone - as traces configured in particular patterns \(spirals, etc\) can produce emergent properties such as magnetism, etc. Traces typically are produced from highly conductive materials like copper and can be integrated with any number of processes from bonding, plating, etching, fusing, knitting, weaving, etc.   
  
Sewing Traces Tutorial:   
[https://www.instructables.com/lesson/Sew-a-Circuit/](https://www.instructables.com/lesson/Sew-a-Circuit/)

Woven Electronic Ribbon integrated into performance garments:  
[http://www.scisci.org/textilen/](http://www.scisci.org/textilen/)  
  
Cut and fused copper fabric example:   
[http://afroditipsarra.com/index.php?/older-projects/cosmic-bitcasting/](http://afroditipsarra.com/index.php?/older-projects/cosmic-bitcasting/)

Knitting traces to make a finger sensor \(see tutorial slides at end of page\):   
[https://blog.jesseseay.com/](https://blog.jesseseay.com/)

Embroidered traces  
[http://www.ireneposch.net/the-embroidered-computer/](http://www.ireneposch.net/the-embroidered-computer/)

## **Connections**

Once you have made your traces, you must then find ways to connect different "components" together. Good connections should be tight, robust and tidy, making sure that they don't break or short your circuit unexpectedly.

There are two primary modes of connecting: soft-to-soft, where both things being connected are flexible and stretchable, or soft-to-hard where you are connecting a soft material to a rigid material \(e.g. a thread to an Arduino\). Soft to hard connections are typically more prone to error than soft to soft. 

There are already really great online resources that show a variety of techniques such as Kobakant's [overview of connection techniques](https://www.kobakant.at/DIY/?p=1272) and detailed descriptions of many methods in their "[Connections" category.](https://www.kobakant.at/DIY/?p=7077) There are [also many techniques in this summary produced by e-textiles summer camp 2017](http://etextile-summercamp.org/2017/summercamp/hardsoft-connections/). 

### Knots

The first method can be simply knotting materials together. In soft-to-soft, this can be as simple as typing a weavers knot, ensuring it will remain tight, and then trimming long ends to ensure against shorting. In soft to hard connections, one typically can knot around the through-hole of a hard component. In this case, it can be wise to coil the material through the hole a few times to ensure good contact between the metal fibers in your soft material and the metal connections on the component you are connecting to. Frequent method of using knots include knotting conductive material around a metal snap and on the other side of the metal snap, soldering on a wire. 

### Structural Integration

When you have conductive materials integrated into your textile structure, one simple possibility is to simply integrate traditional wires into the structure so that the structure, itself, holds the materials in close contact. This is what I did in this project, [essentially twisting soft and more sturdy wires together at weaving time](http://artfordorks.com/2020/04/a-fabric-that-remembers/). In a different project, we soldered silicone coated wires directly to an arduino pro mini and then integrated the arduino into a [pocket within the woven structure, then wound the edges of the wire and yarn together within the fabric itself](http://unstable.design/some-teaser-images-from-our-experimental-weaving-residency/). You can see the FTDI connector pocking out of the fabric below, with the black wires routing through the structure. 

![](.gitbook/assets/img_6837-1024x768.jpg)

### Soldering

Some soft materials can be directly soldered to or soldered upon, allowing for more complex geometries and tightly packed connections. In non-wearable applications, I have had luck twisting a conductive yarn around a looped stranded or solid core wire, and soldering the wire to itself \(catching the thread in between\). 

Soldering to headers from a fabric using a pocket structure:   
[https://www.instructables.com/id/Simple-E-textile-Connector/](https://www.instructables.com/id/Simple-E-textile-Connector/)

### Temporary Connection Methods

There are also alternatives to using something like alligator clips when testing your circuit by using materials, like pins and clips, that have been designed to hold to textile structures.   
  
Irene Posch's Collection of Handmade Connectors for Soft Electronics:   
[http://www.ireneposch.net/tooling/](http://www.ireneposch.net/tooling/)

Adapted Seem Ripper:  
[https://www.plusea.at/?p=2220](https://www.plusea.at/?p=2220) 

## **Insulating**

Methods for isolating your traces so they do not short or cross where you don't want them.   

Common Coatings \(poly, silicone\)  
Core Spun Materials  
****isolating ****layers ****

## **Resistors**

basic structure // resistors are just pieces of material  
techniques for sewing resistors  
weaving resistors  
knitting resistors \(knitted radio examples\)

## **Capacitors** 

knitted capacitors \(knitted radio\)  
woven capacitors

## **Transistor**

I've seen some research published on this, keep looking

## Diode

no idea, need to look

## Switching Structures

Single Switch  
Accelerometer examples  
Press button arrays

## **Resistive Sensors**

overview of fundamentals and wiring diagrams

### Force Sensitive Resistors / Press Sensing

### Stretch Sensing

## **Capacitive Sensors**

fundamentals

**Custom Capacitive Sensing Yarn:** 

According to the original announcement, there were three main challenges in this. First, you needed a yarn that could withstand industrial manufacturing machines. Second, they wanted it to not be grey, and Third, they wanted it to be responsive to capacitive touch. Because they are Google, they were able to work with industrial suppliers to engineer their own yarn which consists of three magnet wires or filaments in the core \(middle\) which were then braided \(on a very fun to watch maypole machine!\) with a dyeable and durable fiber: silk. They used copper because its very conductive; silk because its really strong and dyes into really brilliant colors; and a braided structure because it could withstand large amounts of force. While we can note that this was certainly not the first conductive yarn to be core spun or to allow for capacitive touch sensing, what is interesting is what is possible with you have access to equipment that is otherwise unaccessible. They could really precisely tune the material to the function they hand in mind and the infrastructure that they would need it to work within. 

**Touch using Arduino ADC pin**

**Swept Frequency Capacitive Sensing**

**2D Capacitive Grid**

## Electromagnetic **Sensors**

## Shape Change

pneumatics / jamming

artificial muscles

Lets start with a [McKibben artificial muscle](https://softroboticstoolkit.com/book/pneumatic-artificial-muscles#:~:text=The%20muscles%20consist%20of%20an,radial%20expansion%20into%20linear%20contraction.) which consists of a rope that is braided around a ****hollow tube. When you pressurize the fluid \(air or water\) in the tube, the braided structure amplifies the movement. In most DIY examples, we see these made by simply buying a pre-made braided hollow cord and shoving a hollow tube down the center of it. 

[https://www.youtube.com/watch?v=PYSqkEhVe6k&feature=emb\_title](https://www.youtube.com/watch?v=PYSqkEhVe6k&feature=emb_title)



pleating, folding, switch

auxetic structures \(jifei, benhaz\)

tendons \(lea's paper\)  
  
biologic \(lining\)  


temperature and twist

[https://www.skyscrape.us/](https://www.skyscrape.us/)

## Color Change 

Thermochromic  
 [Maggie Orth](http://www.maggieorth.com/art_100EAYears.html) and others beginning in 2009 and we played around with integrating the yarns in various stitches to see what kinds of effects we could come up with.

Photochromic  
Moisture   
Structural Color \(nano-fabrication // liquid crystal\)  
[https://cen.acs.org/articles/93/web/2015/06/Structural-Color-Nanoparticles-Makes-Bright.html](https://cen.acs.org/articles/93/web/2015/06/Structural-Color-Nanoparticles-Makes-Bright.html)

Victoria Manganiello: Computer 1.0  
[https://vimeo.com/261862777](https://vimeo.com/261862777)  


e-ink  
Bacteria

## Electromagnetic Actuation

embroidered computer

nick collins land

lara grant land

\*\*\*\*
