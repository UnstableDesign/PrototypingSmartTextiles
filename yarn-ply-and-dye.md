---
description: Adding structure and function at the level of the yarn.
---

# Ply and Braid

As I have surveyed projects that use active or "smart" materials within textile structures, I tend to see two kinds of projects: \(1\) those that focus exclusively on the structure and composition of a yarn \(often leveraging braids\) and \(2\) those that use more conventional yarns and integrate them within a fabric to give some sort overall effect, say, touch sensing across the surface of the fabric. Other times, you will buy smart fabrics only to find it was created with standard materials and simply sprayed or coated with something to make it conductive \(which then comes off on your hands\). 

There is a huge opportunity to here to think about textiles from the fiber up and you can't do that unless you consider a critical intermediary: yarn. Now when I say yarn, I don't just mean just cotton or even conductive yarn, I mean anything you can get your hands on that is long, pliable and can be braided or coiled. This includes biomaterials, fishing line, tubing, and hair. The magic happens when we mix all of these wild things together and see if they play nice. 

Before moving into technique, I want to motivate the discussion on yarn, cable and rope by considering a few examples from research and industry. With these, I want to show how combinations of materials can give us very different possibilities. 

**Case 1:  Artificial Muscles**  
Lets start with a [McKibben artificial muscle](https://softroboticstoolkit.com/book/pneumatic-artificial-muscles#:~:text=The%20muscles%20consist%20of%20an,radial%20expansion%20into%20linear%20contraction.) which consists of a rope that is braided around a tube. When you pressurize the fluid \(air or water\) in the tube, the braided structure amplifies the movement. 

In most DIY examples, we see these made by simply buying a pre-made braided cord and shoving a hollow tube down the center of it. 

{% embed url="https://www.youtube.com/watch?v=oBkdKeTJ5NY" %}

Which is actually a really great adaptation to making your own braided structures that folks like Irene Posch have used to make other things, [like custom e-textile "alligator clips"](http://www.ireneposch.net/tooling/). SOme other folks have taken this idea, made longer muscles and woven them through other fabrics to see what shapes they make: 

{% embed url="https://www.youtube.com/watch?v=PYSqkEhVe6k" %}



Okay so lets now combine that with another fun discovery: the fact that when you coil and heat monofilament, nylon fishing line, you can make a single filament that is quite strong: 

{% embed url="https://www.youtube.com/watch?v=Za0VeU9Ov7A" %}

If I'm understanding this video correctly, they have essentially mimicked the braided structure using these nylon muscles to provide even more lifting power to the structure So now you can consider that the tube and pneumatic pump need not even exist, the braid can do its own expanding and contracting. Better yet, these are heat/voltage activated, so you can braid them with conductive or resistive heating wires to integrate the actuating elements uniformly along the length \(or non-uniformly if you're into that kind of thing\). Maybe you want to have some feedback mechanism, like having a reading that tells you how much the muscle is expanding. Well then, just integrate another yarn that change is properties when stretched, perhaps with a change in resistance. Maybe you want to have the system activate on touch. Okay then, just add another yarn that offer capacitive sensing \(or make your hands really hot to by-pass the conductive just get right to the point. How do you make these kinds of things: braiding or plying \(we'll get to that later\). 

And if you're head isn't already spinning with ideas for tubing and braiding, I'll leave you with this:

{% embed url="https://vimeo.com/261862777" %}



**Case 2: Engineering a Production Scale Conductive Yarn.** 

The second case is from Google's Project Jacquard. The story starts with Google wanting to integrate into wearables, and wanting to do it in a really elegant way. According to the original announcement, there were three main challenges in this. First, you needed a yarn that could withstand industrial manufacturing machines. Second, they wanted it to not be grey, and Third, they wanted it to be responsive to capacitive touch. Because they are Google, they were able to work with industrial suppliers to engineer their own yarn which consists of three magnet wires or filaments in the core \(middle\) which were then braided \(on a very fun to watch maypole machine!\) with a dyeable and durable fiber: silk. They used copper because its very conductive; silk because its really strong and dyes into really brilliant colors; and a braided structure because it could withstand large amounts of force. While we can note that this was certainly not the first conductive yarn to be core spun or to allow for capacitive touch sensing, what is interesting is what is possible with you have access to equipment that is otherwise unaccessible. They could really precisely tune the material to the function they hand in mind and the infrastructure that they would need it to work within. 

{% embed url="https://www.youtube.com/watch?v=qObSFfdfe7I" %}

I was able to collaborate with their team during the early stages of this project \(and this experience largely inspired a much deeper dive into textiles after the collaboration\). It took a while before we were able to get this very special yarn, so in the meantime, we used a simpler version that consisted on a single magnet wire plied with silk. This structure is much easier to mimc by hand. What Joanne Lo, another collaborator on the project, noticed about the very few and very tiny yarn samples we did have was that they were really good resistive heaters. Basically, if you pump voltage into a very thin wire, it causes it to heat up. Furthermore, those heating wires were directly in contact with the fabric shell or sheath, meaning that very little heat would be lost. While on one hand, you can imagine a warming jacket or socks, we decided to coat the yarns with thermochromic pigments that change color at different ranges of temperature. This concept had been really beautifully illustrated by [Maggie Orth](http://www.maggieorth.com/art_100EAYears.html) and others beginning in 2009 and we played around with integrating the yarns in various stitches to see what kinds of effects we could come up with.

{% embed url="https://vimeo.com/138025527" %}

So here we say one function sort of serendipitously allowing for another. A later project created in collaboration with Google takes the technology of braiding even further to enable new kinds of interactive sensing upon the yarns itself. This project, particularly, leverages fiber-optics to create input and output. 



{% embed url="https://www.youtube.com/watch?v=t-\_QCI8ntDM" %}

So we see the kind of evolution in thinking when you start imagining how you can spin and braid things around things, adding different functions, sensing, actuation and adaptation at each level. with that in mind, I'll leave you with this image I was able to capture at the Henry Ford Museum of the original transatlantic cable. I couldn't help by love that this cable, this massive innovation moment, was just coils on coils on oils of wire and cable, spun just like yarn. 



![](.gitbook/assets/img_7233%20%281%29.jpg)

![](.gitbook/assets/img_7234%20%281%29.jpg)

Experimentation in smart textiles ought to start at the level of individual yarns as each yarn brings a particular set of qualities, functionality, and compatibilities with specific techniques that you may need to employ. For example, the composition, in both structure and materials, of conductive yarns determines if they gain or lose resistance when stretched to strained, whether they will effectively transmit heat, whether they will short if crossed and whether you can solder to them or not. 













Identifying and sourcing the yarns necessary for smart textiles can be difficult and often forces experimenters to rely on what they can find rather than what might be ideal for their purpose. Furthermore, accessible equipment for precisely making large qualities of rope, cable or yarn are not accessible to most people prototyping smart textiles. Yet, there is a lot to love, and to make use of, in these tubular and winding structures. In some cases, we can imagine functionality that we have considered only to be distributed throughout a fabric, distributed throughout a yarn. 

There are two options we can pursue here separately or together: The first is ordering samples of yarns offered by different suppliers for testing and trying to find one that matches our needs, the other is to somehow creatively combine different yarns and fibers, as well as different structures, to create something that functions more or less how you might like it to. In this chapter, we'll start with an overview of yarn structures and nomenclature before going into more detail about suppliers of individual materials.

\*\*\*\*

## \*\*\*\*

### \*\*\*\*

## Combining Singles into Yarn Structures

Singles are not very strong, as the only thing holding fibers together is the twist. The direction of this twist matters as you add additional structure to the yarn. **Twist, in yarn, is typically described as "Z' twist or "S" twist**. Thus, relative to how you are looking at the yarn, does the winding look more like a Z or an S. This twist makes a difference in how the more compound yarn structures are formed, and also can be leveraged in processes of weaving, where the twist structure allows fabrics to take on three dimensional properties. 

**Plying**

Plying consists of twisting multiple singles together. You can ply with 2, 3, or however the hell many yarns you like, but its probably best to stay on the small side \(under 6\) to keep structure if you are doing this somewhat freehand. For bigger yarns or projects, you'll often see plys of plied yarn which are technically called "cabled" yarns. This is a yarn that is made by plying together previously plyed yarns. 

If you want to ply two yarns together, here is what you do. Each of the singles strands is twisted in one direction \(lets say Z twist\), independently of the other. Once they are all twisted to the desired angle the counter-acting twist is applied from the joined end in the opposite \(or in this case S-direction\) and propagates through the singles, joining them together.

If you were an elegant and details oriented spinner, you would ply like this: 

{% embed url="https://www.youtube.com/watch?v=ibpaZXq1eiU" %}

{% embed url="https://www.instructables.com/id/Conductive-Thread-Wind-up/" %}



And if you were a bit more hasty and just wanted to get it done and somehow involve a drill, you might do it like this: 

{% embed url="https://www.youtube.com/watch?v=2kQBp\_5PPTc" %}

And if you wanted to get the whole village involved, it might look like this: 

{% embed url="https://www.youtube.com/watch?v=toyOKOi0DsM" %}

#### Do it yourself:

If you want to try this, take any string you have nearby, twist it as much as you can between your hands and then fold it, holding the two ends in one hand and the fold in the other. You can watch the ply twist into itself to achieve balance, and if you feel like it, you can help it along and see even more twist. The same goes for plying larger amounts of singles, like in rope making seen below. Each of the 6 strands is twisted in one direction, independently of the other. Once they are all twisted to the desired angle the counter-acting twist is applied from the joined end and propagates through the singles, joining them together.

In the lab, we have found the most practical way of plying together fibers and filaments, without a drill and without a spinning machine, has been to use a simple drop spindle \(like pre-historic weavers\). In this demonstration, we show how you quickly ply your yarns together.  

![The steps of plying with the drop spindle.](.gitbook/assets/compound-image.png)

Emeteuz shows us how this comes in hand when we need to make long lengths of our own conductive thread:

{% embed url="https://vimeo.com/93086189" %}

In this video, she is hand spinning heating wire for activating thermochromic pigments on yarn. By spinning the materials together \(instead of ironing a heating element on the back of the fabric\) she's ensuring there is really good transfer between the yarn and the heating element. As we found in our own studies, any air that comes between these two can drastically extend or reduce the activation time for the yarn to change color. 

## Describing Yarns

So now that we understand that yarns are made of twisted fibers, which have then become into much larger and stronger plyed or cabled fiber, we may come to understand the numbers that people use to describe yarns. Its also important to note that there are many different measures depending on what you want to describe and not all yarns are spun equal. You can add lots of spin, a little spin, lots of ply, a few plys and so on and so on and each will change the behavior. Futhermore, the ways that yarn is described for knitting is not always the same way yarn is described for weaving \(they are, after-all, very different processes\).Then we add conductive things to this mix and all the sudden we have to deal with conventions in the way wires are measured. 



Thankfully, there are terms that help us understand the properties that make the most impact and characterize different yarns.

https://www.youtube.com/watch?v=G4MuKCCNoCk

[Wraps per inch](https://www.craftyarncouncil.com/standards/how-measure-wraps-inch-wpi): This measure the width of the yarn. It is measured by counting how many wraps you can make around a length of 1 inch. Careful, pulling or not pulling the yarn will change this, best to shoot for a tension somewhere in the middle.

https://www.youtube.com/watch?v=FckfIcDU52o

[Gauge](https://www.craftyarncouncil.com/standards/yarn-weight-system): This measures how many stitches \(knitting\) you can fit within a four inch row of stockinette knit. The category of gauge is one of the most common when purchasing yarn, and also determines the size or your tools. I found this horribly confusing when I was learning, so its useful to have a guide.  Woven fabrics typically use different measures such as warps-per-inch which vary on the stitch...but more on that later.

Twist Angle: A measure how how tightly the yarn is twisted. This matters because you may find that the amount of twist greatly changes the behavior of your fabric, especially when you are looking for textured or three-dimensional effects in the textile. [There are really fancy ways to measure twist precisely](https://textilestudycenter.com/twist-measurement-in-yarn/), but for the most part you can use a protractor and some careful looking to determine the twist angle. The higher the angle the tighter the twist.











 

















 In this spirit, we present a few more custom yarn techniques to stimulate the imagination of what might be possible for smart textiles with better control over yarn production:

#### Rope Making

  
 A designer can create custom “ropes” by taking several lengths of yarn tied to a peg \(or one continuous loom wound around a peg\) and tying them to individually rotating hooks. When one turns the hooks with the yarns under tension, all lengths of yarn twisted individually and equally. When one “relaxes” the apparatus, the individual yarn lengths recoil and spin upon each other. The thickness of the resulting rope depends on the thickness of the individual materials that comprise the rope. We tried this technique, using a Schacht Incredible Rope Machine, to combine our yarns and heating wires \(Figure 9b\). While the resulting yarn had many sections of heating wire per unit length, it was difficult to make ropes without breaking. However, the design of rope making systems can be adapted such that the twisted wires wrap around a “core” that would sit in the center. In this sense, we can envision future research studying how brittle heating \(or other\) wires could be placed in the core with several lengths of color-changing threads spun around them.

#### Knitted Tubes

Figure 9: examples of custom yarn structures  
 We have also conducted several experiments, for a different soft sensor project that used knitted tubes to create a smart string \(Figure 9d\) \[11\]. We used a Caron EmbellishKnit hand crank device to knit together a long conductive yarn with a long non-conductive yarn. In this project, we found that smoother or coated conductive yarns worked best to prevent the conductive yarns from grabbing the others. The hollow knitted tube also makes it possible to insert a core. Since the resulting structure is knitted from continuous lengths of yarn, it is quite stretchy and flexible. We also used this structure in the past to create force-sensitive yarns by knitting conductive yarns around a Velostat core, which worked well. 

#### Kumihimo Braiding

Kumihimo braiding is a technique in which several lengths of yarns are braided into hollow tubes \(Figure 9c\). Kumihimo templates can be used to create braids with custom textures and patterning. The templates are easy to produce in cardboard on a laser cutter at various thicknesses. During this braiding, the maker has more control over tensions than they might with techniques that spin yarns together, thus, they may be ideal for applications that require brittle materials to be integrated into the outer structure of the yarn.









This week, we'll scale up once more to consider how multiple materials in string or filament form come together to form yarn, rope, cable. This starts some some basic techniques and elements which can continually be repeated and combined with other techniques to produce a variety of material/structures, each of which offers its own distinctive set of functional, mechanical, and aesthetic properties.

The transition from fibers to threads helps further enhance or augment the fiber's or blend's properties as well as provides for the refinement of strength, stretch, memory, durability, etc. In electronics applications, the specific way the fiber is integrated into yarn, rope or cable allows for the customization of features such as conductivity, insulation, resistance changes, heat production, signal clarity, etc.

For the sake of putting these techniques into context, I will describe techniques as they have developed through time. What I find most interesting is the way that techniques developed more than [20,000 years ago](http://www.smithsonianeducation.org/educators/lesson_plans/spinning_yarns/ATZ_SpinningYarns_Sep1980.pdf) are still the primary method of production today. For example, if we look at the biggest advances in modern science, such as the transatlantic cable, fiberoptics or your local 5G network, you'll find that they are simply yarns of another kind that weave together networks instead of literal fabrics. To get a bit poetic, you can imagine that networks are simply the clothes that surround the globe and exist as much materially, as literal cables that wash along the shore, as they do within the air.

**Brief History of Spinning**

![](http://unstable.design/wp-content/uploads/2020/07/spinning-women1-750x375.jpg)

With evidence to suggest that spinning yarn was taking place over 20,000 years ago, spinning continues to be one of the primary methods of producing yarn, though the social and cultural politics of that production has changed over time.

The earliest spinners attached raw fibers \(of wool, flax, etc\), to a spindle. The spindle was tossed in such a way that is spun through the air as the spinner fed it with fibers. For those interested in how these techniques varied in medieval times by region, you may enjoy this demonstration of technique.

https://www.youtube.com/watch?v=RERnzaTREyM

As cloth became a major commodity in [China, India, and Islamic regions, the demand for yarn rose and people started to search for faster ways to spin yarn](https://quatr.us/china/invented-spinning-wheel-history-spinning.htm). The **spinning wheel**, of fairy tales and fables, was developed [between 500 and 1000 AD though the region of the invention is contested](https://americanhistory.si.edu/collections/search/object/nmah_1200991#:~:text=The%20process%20predates%20written%20history,those%20making%20fiber%20into%20yarn.) \(some say India, others China or Iran\). [Some argued the origins of the spinning wheel trace to China as well](https://www.thoughtco.com/spinning-wheel-evolution-1992414). You might say that the spinning wheel was the first step towards industrialization in textiles and by the 14th century, the Chinese had come up with water-powered spinning wheels. The power of the wheel is this is could turn faster and for longer than a hand spinner.

![](http://unstable.design/wp-content/uploads/2020/07/spinningwheel.jpg)ng wheel in Baghdad \(al-Wasit, 1237 AD\)

**How Yarn in Spun**  
  
 Present day spinning happens by a community of hand-spinners as well as industrial textile mills, each of which automate the spinning process for a specific fiber and structure and typically do everything from processing the raw fiber, spinning the yarn, and weaving fabrics. Each process of spinning, specifically, adds specific characteristics to the yarn, for instance, making it thicker, more wirey, or more fluffy determined, in large part, by the amount of twist given to the fibers. When hand spinning, you have much more room for experimentation with these techniques, and the ways in which they production yarn with radically different properties and textures. Because we're thinking of ways to adapt these processes to our own experiments, and we don't have textile factories readily available, I'll focus on the hand techniques.

**Hand Spinning**  
 Most hand-spinners spin on present-day spinning wheels. These require total coordination between hands and feet as the spinner uses foot pedals to keep the wheel spinning at a constant and desired rate, and carefully draws fibers into the wheel to achieve their desired yarn. The yarn typically goes through processes of plying or finishing, which enhance or draw out other characteristic.

The hand-spinning process starts by obtaining fibers which are sold in **worsted** or **woolen** form. Worsted means that the fibers are combed so that they all align in the same direction and are of uniform length. This is often used for making yarns that are more  uniform, lustrous in color, durable, and a little wirey. Packages of worsted fiber are called "top" and you can buy them for your own hand-spinning projects.

Woolen means that the fibers are "carded" which "encourages the fibers to lie in multiple directions" \[yarn-i-tec-ture\]. Fibers of all different lengths are kept in this process. The goal of carding is to build up enough of a "mesh" of fibers that they hold together. These meshes, and the process, yields more airy, fluffy and soft yarns. Bundles of worsted fibers are most often called "roving" but you different preparations go by names batts, rolags, fauxlags, puin, cloud, and wool locks, each of which offers, as you expect, its own set of unique qualities to the fibers.

https://www.youtube.com/watch?v=3U3fWNJLVyw

To make matters more confusing, the terms worsted and woolen also describe techniques you can use to feed or "draft" the fibers from your top or roving into the wheel.  These, again, allow for more or less air to become trapped into the yarn, changing its thickness, durability, and likely its capacity for insulation \(I'm guessing, since air is a good insulator\). I won't get into the specifics of how to draft with each of these techniques, but I'm finding the book "Yarn-i-tec-ture" to be a great resource for those interested in going farther. The main point here is to say that the process of spinning is far from uniform. Even if you are spinning with the exact same fiber, the preparation and spin will result in very different properties.

The final step in yarn production is finishing, by which the yarn can be washed, steamed, lassoed, whacked, menaced, and a whole host of other hilarious words, to help the yarn achieve is final state. This is essentially a process of making the yarn resemble the state you want it to stay in and you really don't know much until you've washed and laundered a textile project \(which is always frightening to me\).

**Plying**

After you have spun your top or roving into a continuous string of yarn, you have created what is known as a "single" or singles yarn. Sometimes, this yarn is still too fragile or delicate for your applications but it can be great for really dainty and delicate things like lace. You \(and most manufacturers\) create more strength through the process of plying.

Plying consists of twisting multiple singles together. You can ply with 2, 3, or however the hell many yarns you like, but its probably best to stay on the small side \(under 6\) to keep structure if you are doing this somewhat freehand. For bigger yarns or projects, you'll often see plys of plied yarn which are technically called "cabled" yarns. This is twisted yarn that is made from many other twisted yarns. Typically, you will "ply" or twist together your singles in the opposite twist direction of the singles themselves. If you want to try this, take any string you have nearby, twist it as much as you can between your hands and then fold it, holding the two ends in one hand and the fold in the other. You can watch the ply twist into itself to achieve balance, and if you feel like it, you can help it along and see even more twist. The same goes for plying larger amounts of singles, like in rope making seen below. Each of the 6 strands is twisted in one direction, independently of the other. Once they are all twisted to the desired angle the counter-acting twist is applied from the joined end and propagates through the singles, joining them together.

https://www.youtube.com/watch?v=toyOKOi0DsM

Plying can be done of a spinning wheel if you have long lengths of yarn that you want to

Thankfully, there are terms that help us understand the properties that make the most impact and characterize different yarns.

https://www.youtube.com/watch?v=G4MuKCCNoCk

[Wraps per inch](https://www.craftyarncouncil.com/standards/how-measure-wraps-inch-wpi): This measure the width of the yarn. It is measured by counting how many wraps you can make around a length of 1 inch. Careful, pulling or not pulling the yarn will change this, best to shoot for a tension somewhere in the middle.

https://www.youtube.com/watch?v=FckfIcDU52o

[Gauge](https://www.craftyarncouncil.com/standards/yarn-weight-system): This measures how many stitches \(knitting\) you can fit within a four inch row of stockinette knit. The category of gauge is one of the most common when purchasing yarn, and also determines the size or your tools. I found this horribly confusing when I was learning, so its useful to have a guide.  Woven fabrics typically use different measures such as warps-per-inch which vary on the stitch...but more on that later.

Twist Angle: A measure how how tightly the yarn is twisted. This matters because you may find that the amount of twist greatly changes the behavior of your fabric, especially when you are looking for textured or three-dimensional effects in the textile. [There are really fancy ways to measure twist precisely](https://textilestudycenter.com/twist-measurement-in-yarn/), but for the most part you can use a protractor and some careful looking to determine the twist angle. The higher the angle the tighter the twist.

Twists Per Inch:

"A thin yarn with less fiber needs more twist in your yarn

https://www.youtube.com/watch?v=8JEpSeDobpo

https://www.youtube.com/watch?v=zYkglUysDKk

https://www.youtube.com/watch?v=FrZcr7\_qXFY

https://www.youtube.com/watch?v=toyOKOi0DsM

https://www.youtube.com/watch?v=UyDHBNix6hA

https://www.youtube.com/watch?v=Cbcf6aEov1Q

https://www.studiohilo.com/what-we-offer

https://www.youtube.com/watch?v=9i9pwaZ8ZaE

https://www.youtube.com/watch?v=z7WH4ilni3M

https://www.youtube.com/watch?v=e0jKRZ5sWx0

https://www.youtube.com/watch?v=D1QKoLUxjeQ

![](http://unstable.design/wp-content/uploads/2020/07/CoreSpunYarn.jpg)

https://dl.acm.org/doi/pdf/10.1145/2858036.2858176

https://www.sciencedirect.com/topics/engineering/core-spun-yarn

https://www.youtube.com/watch?v=fjRqGKU9cUU

https://www.designsponge.com/2012/02/diy-project-sculptural-braided-extension-cords.html

http://www.ireneposch.net/tooling/

https://www.youtube.com/watch?v=QmqzxCcXeSA

https://www.researchgate.net/figure/Preparation-procedures-for-the-two-ply-yarn-supercapacitors\_fig1\_260427879

https://www.youtube.com/watch?v=RERnzaTREyM

