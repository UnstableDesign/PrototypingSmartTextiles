# Programmable Color Changing Fabric
This activities focuses on the creation of a programmable color changing yarn, which can then be knit, woven, or otherwise combined into a programmable color changing fabric. 

![Thermochromism in Action. Heating the yarn turns the color transparent. The color returns to the yarn as it cools](../../.gitbook/assets/img_9999-animation.gif)



## How Does it Work?
This project leverages thermochromism, the quality of paritcular pigments or dyes to change from a color to transparent above a specified temperature. Specifically, heat causes the chemical structure of the pigments to change, leading our eye to percieve them as either a solid color or transparent. If we use electrical components to provide the heat needed for color change to occur, then we can essentially "program" the color changes by turning the heating elements on and off. 

## Steps
There are many ways to combine fiber, pigments, heat, and electronics but we'll focus on: 
 1. creating a thermochomic paint or prepping a thermochromic dye
 2. applying the paint/dye mixture to fibers
 3. creating a tight coupling of heating wire to fiber
 4. creating circuitry to programmatically power the heating wire. 

 ## Materials
 * [heat activated thermochromic dye](https://solarcolordust.com/hue-chromic-fabric-dye-violet-to-colorless/)
 * or [heat activated thermochromic pigment](https://solarcolordust.com/thermal-dust-86-f-violet-to-colorless-heat-sensitive/)
    * while you can buy dyes and pigments that transition between colors, I prefer to use pigments/dyes that trandition from color to colorless at about 86 celcius. I find bold colors (dark blues, greens, violets) have a more interesting visual effect than lighter colors (reds, pinks, yellows). The dyes produce a better hand quality on the fiber but tend to only produce muted tones, if you want darker and more concentrated color you are better off mixing your pigments with a [transparant acryllic gel medium](https://www.dickblick.com/products/liquitex-gel-mediums/?clickTracking=true&wmcp=pla&wmcid=items&wmckw=00618-3165&gclid=CjwKCAjw8sCRBhA6EiwA6_IF4YLEmriXEcbG7lV0gJeTiBrytFw7B2L24j-1NrFWcqPBLcE_hVmjqxoCqEEQAvD_BwE). This essentially suspends the pigments in a paint and the the higher the pigment/paint ratio is on mixing, the bolder the color. 
* [fiber based material] (../structure/staple-fiber.md) 
    * if using the dye, your fiber should be a [cellulose-based](../materials/cellulose-fibers) material like cotton. If using the painting method, any fiber structure (paper, yarn, fabric, etc) can be used. For this specific lesson, we'll use wool yarns. I like working with wool because it holds heat nicely, allowing the effects of the color change to last a bit longer. 

* [magnet wire](https://www.remingtonindustries.com/magnet-wire/magnet-wire-38-awg-enameled-copper-6-spool-sizes/?gclid=CjwKCAjw8sCRBhA6EiwA6_IF4RPkDroQ8fdHSGAWr0U1CUQ_PQBx6CuAjjQzyjz94G6TkJJLdA7T0BoC8cQQAvD_BwE)
    * magnet wire makes for a great heating element. The thinner the wire, the more heat produced (see [Joule heating](https://en.wikipedia.org/wiki/Joule_heating) for more on the physics of this). I think 38 AWG (AWG = American Wire Gauge, a measure of the diameter of the wire) is about the thinnest yarn that's workable without breaking.  Fun fact, the higher the AWG, the thinner the wire. 

* crimp beads
* arduino microcontroller and jumper wires
* (optional) external power supply
* [N-Type MOSFET] (https://www.adafruit.com/product/355) 

## Tools
* painting or dying tools 
* [drop spindle](../process/)
* crimp beads 
* sand paper
* wire cutters and clamps








#### Online Resources

* [Plying Custom Conductive/Color-Changing Yarn](https://vimeo.com/93086189),  ****[Anne-Marie Lavigne](http://emeteuz.com/woven-signals) 
* [DIY Drop Spindle](https://www.youtube.com/watch?v=PKSLiUGJUo8) [Creativebug Studios](https://www.youtube.com/channel/UC5Kp8JjsqrtlqeIF7RgatPg)\*\*\*\*

