---
title: Dynamics
weight: 4
bookCollapseSection: true
---

# Dynamics

We use the term dynamics to describe different methods for making the textiles change in response to external stimuli. These might include the introduction of electricity into the textile structure, the integration of non-tradiitonal materials into textile structures to support shape or color change or structures that have unique mechanical properties. 

## Electrical Components
When working with electricity in textiles (e-textiles), what is required is metal yarn, thread, or flexible wire. A metal yarn conducts electricity meaning it can carry electicity from a battery or power source to a series of loads (things within the cirucuit). The metal yarn acts as the [trace](./traces.md) or route for the electicity between components in the same way a wire connects components in a traditional circuit. In fact, you can sew or weave with normal wires as well, and I reccomend [30 AWG silicone coated wires](https://www.amazon.com/BNTECHGO-Silicone-Flexible-Resistant-Insulation/dp/B01M70EDCW/ref=sr_1_12?crid=1R6D4MFI6V116&keywords=32+awg+silicone+wire&qid=1664763990&qu=eyJxc2MiOiIyLjk0IiwicXNhIjoiMi41MiIsInFzcCI6IjIuMTQifQ%3D%3D&s=industrial&sprefix=32+awg+silicone+wir%2Cindustrial%2C109&sr=1-12) as being nicely conductive and flexible with an insulated coating to prevent shorts. 

## Circuit Basics

If you remember your grade-school science lessons, you might remember learning about electricity with an example like this: 

![](/led_in_simple_direct_current_circuit.jpg)

\_\_[_Creative Commons_](https://en.wikipedia.org/wiki/Creative_Commons) __[_CC0 1.0 Universal Public Domain Dedication_](https://creativecommons.org/publicdomain/zero/1.0/deed.en)_,_ [_https://en.wikipedia.org/wiki/File:LED\_in\_simple\_Direct\_Current\_Circuit.JPG_](https://en.wikipedia.org/wiki/File:LED_in_simple_Direct_Current_Circuit.JPG)\_\_

Here, the power leaves the battery on the + side, travels across the black lines \(wires\) and then flows through points B, C, D. Along the way, in this example, it encounters, a light and then a resistor become continuing to ground \(-\). This same principle holds in smart textiles, [though we tend to use conductive yarns instead of wires](https://lbruning.com/etextilelounge/scotch-tape-and-conductive-thread/) or we use wires, but we weave or knit them into the structure of the textile, hooking up different components along the way. 

A conductive material is one through which electricity can flow, and they most often include some metallic component. [Lynne Bruning gives an excellent intro into testing your yarns for conductivity](https://www.youtube.com/watch?v=SwiaXMpoy-o). To test, you'll need a [multimeter and SparkFun offers a nice tutorial for how to use a multimeter](https://learn.sparkfun.com/tutorials/how-to-use-a-multimeter/all). For testing conductive threads and yarns, I recommend buying "[minigrabber](https://www.digikey.com/product-detail/en/pomona-electronics/3782-24-02/501-1458-ND/736648?utm_adgroup=Test%20Leads%20-%20Banana%2C%20Meter%20Interface&utm_source=google&utm_medium=cpc&utm_campaign=Shopping_Product_Test%20and%20Measurement_NEW&utm_term=&utm_content=Test%20Leads%20-%20Banana%2C%20Meter%20Interface&gclid=CjwKCAjw2Jb7BRBHEiwAXTR4jYPu0rJsKwnSFFHZf3t3u9UcSv2Ebu5TrewrD8XqVc0xIEi2fsIh1RoC2J0QAvD_BwE)" leads for your multimeter, which make it easier to hold the yarns during testing. 

[SparkFun](https://www.sparkfun.com/?gclid=CjwKCAjw2Jb7BRBHEiwAXTR4jV1vDM50CJQN6W0JDZvkK222x-WAjj5FLbif2daxkJdnIra-RqvXbBoCHXAQAvD_BwE) also offers great lessons on this topic as well: 

* [What is Electricity?](https://learn.sparkfun.com/tutorials/what-is-electricity)
* [Voltage, Current, Resistance, and Ohm's Law](https://learn.sparkfun.com/tutorials/voltage-current-resistance-and-ohms-law)
* [What is a Circuit](https://learn.sparkfun.com/tutorials/what-is-a-circuit)
* [Series vs. Parallel Circuits](https://learn.sparkfun.com/tutorials/series-and-parallel-circuits)
* [How to Use A Multimeter](https://learn.sparkfun.com/tutorials/how-to-use-a-multimeter)
* [Metric Prefixes](https://learn.sparkfun.com/tutorials/metric-prefixes-and-si-units)

### Resistance

One of the most critical points to understand for learning smart textile, or when beginning, is a deep understanding of resistance and how it varies \(by shape, temperature, material and cross-sectional area\). This helps us understand how we can use resistance as a way to measure changes to our soft structures and whether or not those changes mean what we think they mean. It will also help in determining your material choice of any conductive materials. I found [Khan Academy](https://www.khanacademy.org/science/ap-physics-1/ap-circuits-topic/current-ap/v/circuits-) to be an excellent resource for me to brush up on my understanding of circuitry and resistance in general. Its also worth noting that most circuits we will be describing operate on direct current \(or DC\).     

Resistance is a measure of how easily the electric current as it flows through a length of material. It is measured in Ohms \(Ω\). Materials that carry lots of electricity have low resistance and are called conductive materials. Materials that don't carry electricity easily \(but still move it from A to B\) have high resistance and are called resistive materials. The amount of resistance you measure will be proportional to the length you are measuring \(short lengths of a given material will have a lower resistance than long lengths of a given material -- assuming the materials you are measuring has the same diameter/area and is at the same temperature\). 

### Capacitance

Capacitance is a second principle that is important for smart textiles. Capacitance describes the amount of charge that builds up between conductive objects that are not touching--most often represented as conductive plates. Changes in capacitance tell you how close or far another conductive/grounded object is from your circuit. 

## Controlling the Flow of Electricity

Electricity flows from power \(often from a battery, wall outlet, or microcontroller to ground. 

Traces are another way that electricity gets from one place to another. It is a particular path of for electricity to follow and are made from conductive materials. We catalog several method for textile based traces on the [Traces](traces.md) page. [Insulation](insulation.md) describes materials that do not allow electricity to flow through them. When paired with traces, insulation allows you to block electricity from flowing in particular directions. The flow of electricity can be turned on or off, or routed in different directions through [buttons and switches](buttons-and-switching.md). To flow electricity through various components in a circuit, you will need to explore different methods for [connecting](connections.md) things together. This can be as simple as a knot or more complicated if you need to connect you soft textile circuit to a hard material. 

<!-- ### Some Simple Strategies for Weaving Circuits
Sometimes you may not be ready to craft your entire sensor, in which case you can basically just embed a normal circuit into a textile form by weaving (or sewing) a pocket that is large enough to fit the component and then routing the wires to a batter held in another pocket. Connect your components together with [crimp beads, metal snaps](https://www.kobakant.at/DIY/?p=1272), or [custom connectors](http://www.ireneposch.net/tooling/).  -->



## Sensors
E-textiles have shown to be able to support the creation of many form of sensing and actuation. A sensor is something that changes its electrical signal in response to a mechanical deformation. In e-textiles, many times this takes place by measuing changes in resistance, for example, when the electical path is able to shorten in response to particular movement. Many of the structures of textiles inherently become sensors when you weave in metal threds and [Kobakant](https://www.kobakant.at/DIY/?cat=26) shows many possibilities for this. THe main point is that e-texiltes pracitioners are not usually buying pre-made sensors and attaching them to fabric, they are re-inventing the sensors within the [structures](../structure/_index.md) of texiltes themeslves. 



## Actuators  

Actuators describe arrangements of materials where some change in their state is triggered by electrical stimulus. These include motors \([electromagnets](electromagnet.md)\), [speakers](speakers-microphones.md), and [state-changing materials](physical-state-change.md). Actuators typically require power loads beyond what textile systems can support but are achievable through the clever use of [pully systems](https://dl.acm.org/doi/fullHtml/10.1145/3290605.3300414), shape memory alloys, or [electro-magnets](./speakers-microphones.md), [heat-responsive color-changing materials](../quickstart/thermochromics.md), [pneumatic tubing](./physical-state-change.md). 


<!-- ## Harvesters

This is a category that I hear people use, and assume its meaningful, but it describes arrangements of materials where physical stimuli induce electrical power into the circuit. These include solar cells, piezoelectric materials and structures that can generate energy from electromagnetic waves.  -->

## Microcontrollers

A [microcontroller](https://www.youtube.com/watch?v=RmD7UgKvUnY) is a tiny computer designed specially to make sense of the electrical changes coming from your circuit. An Arduino,  is a very common microcontroller for hobby projects and a great general purpose board with tons of tutorials. I have found Teensy great for audio projects and Raspberry Pi is great for projects that need more processing power. 

## Non-Electrical Components
Response textiles may not require electricity and some might argue amterials like wool, which regulate body temperature or offer anti-microbial benefits are already responsive. 

When it concerns shape changing "3D" Textiles, many have explored the use of overtwisted yarns as a means of addign elasticity and self-shaping into the textile structure. Similar one-way deformations are possible with the integration of heat-shrinking and dissolving yarns as well. See Ann Sutton [Weaving Textiles That Shape Themselves](https://books.google.com/books/about/Weaving_Textiles_That_Shape_Themselves.html?id=ni_7ygAACAAJ)


