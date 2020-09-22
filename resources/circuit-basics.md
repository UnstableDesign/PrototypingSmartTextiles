# Circuitry Basics

If you remember your grade-school science lessons, you might remember learning about electricity with an example like this: 

![](../.gitbook/assets/led_in_simple_direct_current_circuit.jpg)

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

Electricity flows from power \(often from a battery, wall outlet, or [microcontroller](circuit-basics.md#microcontrollers)\) to ground. 

Traces are another way that electricity gets from one place to another. It is a particular path of for electricity to follow and are made from conductive materials. We catalog several method for textile based traces on the [Traces](../dynamics/traces.md) page. [Insulation](../dynamics/insulation.md) describes materials that do not allow electricity to flow through them. When paired with traces, insulation allows you to block electricity from flowing in particular directions. The flow of electricity can be turned on or off, or routed in different directions through [buttons and switches](../dynamics/buttons-and-switching.md). To flow electricity through various components in a circuit, you will need to explore different methods for [connecting](../dynamics/connections.md) things together. This can be as simple as a knot or more complicated if you need to connect you soft textile circuit to a hard material. 



## Sensors

A sensor describes an arrangement of materials that changes its electrical properties in response to some external stimulus \(light, pressure, proximity, electromagnetic fields\). These changes in the electrical properties can be measured by multimeter, micro-controller, and/or computer, and thus, can be used to trigger certain computational processes.  Sensors are sometimes classified by the property that is tracked for changes. In this book we have sections devoted to [resistive sensors](../dynamics/resistive-sensors.md), [capacitive sensors](../dynamics/capacitive-sensors.md), and sensors that detect electromagnetic fields \([microphones](../dynamics/speakers-microphones.md)\) and/or radio waves \([antennas](../dynamics/aentennas.md)\). 

## Actuators  

Actuators describe arrangements of materials where some change in their state is triggered by electrical stimulus. These include motors \([electromagnets](../dynamics/electromagnet.md)\), [speakers](../dynamics/speakers-microphones.md), and [state-changing materials](../dynamics/physical-state-change.md)

## Harvesters

This is a category that I hear people use, and assume its meaningful, but it describes arrangements of materials where physical stimuli induce electrical power into the circuit. These include solar cells, piezoelectric materials and structures that can generate energy from electromagnetic waves. 

## Microcontrollers

A [microcontroller](https://www.youtube.com/watch?v=RmD7UgKvUnY) is a tiny computer designed specially to make sense of the electrical changes coming from your circuit. An Arduino,  is a very common microcontroller for hobby projects and a great general purpose board with tons of tutorials. I have found Teensy great for audio projects and Raspberry Pi is great for projects that need more processing power. 



