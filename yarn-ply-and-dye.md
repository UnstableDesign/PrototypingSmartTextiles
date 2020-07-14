---
description: Adding structure and function at the level of the yarn.
---

# Ply and Braid

As we have surveyed projects that use active or "smart" materials within textile structures, we tend to see two kinds of projects: \(1\) those that focus exclusively on the structure and composition of a yarn \(often leveraging braids\) and \(2\) those that use more conventional yarns and integrate them within a fabric to give some sort overall effect, say, touch sensing distributed across the fabric. Other times, you will buy smart fabrics only to find it was created with standard materials and simply sprayed or coated with something to make it conductive \(which then comes off on your hands\). 

There is a huge opportunity to here to think about textiles from the fiber up and you can't do that unless you consider a critical intermediary: yarn. Now when we say yarn, we don't just mean just cotton or even conductive yarn, we mean anything you can get your hands on that is long, pliable and can be braided or coiled. This includes biomaterials, fishing line, tubing, hair, and so on. The magic happens when we mix all of these wild things together and see what magical things happen.

## Motivating Examples

Before moving into technique, I want to motivate the discussion on yarn, cable and rope by considering a few examples from research and industry. With these, I want to show how combinations of materials into different structures can give us very different possibilities. 

### **Case 1:  Artificial Muscles**

Lets start with a [McKibben artificial muscle](https://softroboticstoolkit.com/book/pneumatic-artificial-muscles#:~:text=The%20muscles%20consist%20of%20an,radial%20expansion%20into%20linear%20contraction.) which consists of a rope that is braided around a ****hollow tube. When you pressurize the fluid \(air or water\) in the tube, the braided structure amplifies the movement. In most DIY examples, we see these made by simply buying a pre-made braided hollow cord and shoving a hollow tube down the center of it. 

{% embed url="https://www.youtube.com/watch?v=oBkdKeTJ5NY" %}

Which is actually a really great adaptation to making your own braided structures that folks like Irene Posch have used to make other things, [like custom e-textile "alligator clips"](http://www.ireneposch.net/tooling/). Some other folks have taken this idea, made longer muscles and woven them through other fabrics to see what shapes they make: 

{% embed url="https://www.youtube.com/watch?v=PYSqkEhVe6k" %}



Okay so lets now combine that with another fun discovery: the fact that when you coil and heat monofilament, nylon fishing line, you can make a single filament that is quite strong: 

{% embed url="https://www.youtube.com/watch?v=Za0VeU9Ov7A" %}

If I'm understanding this video correctly, they have essentially mimicked the braided structure of McKibben muscles using these nylon muscles to provide even more lifting power to the structure So now you can consider that the tube and pneumatic pump need not even exist, the braid can do its own expanding and contracting. Better yet, these monofilament muscles are heat/voltage activated, so you can braid them with conductive or resistive heating wires to integrate the actuating elements uniformly along the length \(or non-uniformly if you're into that kind of thing\). Maybe you want to have some feedback mechanism, like having a reading that tells you how much the muscle is expanding. Well then, just integrate another yarn that [change is properties when stretched](https://softroboticstoolkit.com/smart-braids), perhaps with a change in resistance or inductance. Maybe you want to have the system activate on touch. Okay then, just add another yarn that offer capacitive sensing \(or make your hands really hot to by-pass the conductive just get right to the point. How do you make these kinds of things? Answer: braiding or plying \(we'll get to that later on this page\). 

And if you're head isn't already spinning with ideas for tubing and braiding, I'll leave you with this:

{% embed url="https://vimeo.com/261862777" %}



### **Case 2: Engineering a Production Scale Conductive Yarn.** 

The second case is from Google's Project Jacquard. The story starts with Google wanting to integrate into wearables, and wanting to do it in a really elegant way. According to the original announcement, there were three main challenges in this. First, you needed a yarn that could withstand industrial manufacturing machines. Second, they wanted it to not be grey, and Third, they wanted it to be responsive to capacitive touch. Because they are Google, they were able to work with industrial suppliers to engineer their own yarn which consists of three magnet wires or filaments in the core \(middle\) which were then braided \(on a very fun to watch maypole machine!\) with a dyeable and durable fiber: silk. They used copper because its very conductive; silk because its really strong and dyes into really brilliant colors; and a braided structure because it could withstand large amounts of force. While we can note that this was certainly not the first conductive yarn to be core spun or to allow for capacitive touch sensing, what is interesting is what is possible with you have access to equipment that is otherwise unaccessible. They could really precisely tune the material to the function they hand in mind and the infrastructure that they would need it to work within. 

{% embed url="https://www.youtube.com/watch?v=qObSFfdfe7I" %}

I was able to collaborate with their team during the early stages of this project \(and this experience largely inspired a much deeper dive into textiles after the collaboration\). It took a while before we were able to get this very special yarn, so in the meantime, we used a simpler version that consisted on a single magnet wire plied with silk. This structure is much easier to mimc by hand. What [Joanne Lo](https://www.linkedin.com/in/joanneclo), another collaborator on the project, noticed about the very few and very tiny yarn samples we did have was that they were really good resistive heaters. Basically, if you pump voltage into a very thin wire, it causes it to heat up. Furthermore, those heating wires were directly in contact with the fabric shell or sheath, meaning that very little heat would be lost. While on one hand, you can imagine a warming jacket or socks, we decided to coat the yarns with thermochromic pigments that change color at different ranges of temperature. This concept had been really beautifully illustrated by [Maggie Orth](http://www.maggieorth.com/art_100EAYears.html) and others beginning in 2009 and we played around with integrating the yarns in various stitches to see what kinds of effects we could come up with.

{% embed url="https://vimeo.com/138025527" %}

So here we say one function sort of serendipitously allowing for another. A later project created in collaboration with Google takes the technology of braiding even further to enable new kinds of interactive sensing upon the yarns itself. This project, particularly, leverages fiber-optics to create input and output. 



{% embed url="https://www.youtube.com/watch?v=t-\_QCI8ntDM" %}

So we see the kind of evolution in thinking when you start imagining how you can spin and braid things around things, adding different functions, sensing, actuation and adaptation at each level. 

### **Finding Roots to these Projects in History:** 

With that in mind, I'll leave you with this image I was able to capture at the Henry Ford Museum of the original transatlantic cable. I couldn't help by love that this cable, this massive innovation moment, was just coils on coils on oils of wire and cable, spun just like yarn. 

![](.gitbook/assets/img_7233%20%281%29.jpg)

![Sections of the transatlantic cable photographed at the Henry Ford Museum](.gitbook/assets/img_7234%20%281%29.jpg)

## Creating Tubular Structures 

Singles, the first stage yarns created just after spinning are not very strong, as the only thing holding fibers together is the twist. Commonly, these singles are spun into larger, stronger structures. There are several techniques to create these structures and each can work with singles, filaments or a combination of both. The first technique is **plying,** where the yarns are twisted into each-other to create stability. The second is **cabling**, where multiple plied strands are plied again into each other. The third is **braiding**, where a circular braid, like a finger trap, is created to give structure and stability.  

#### Key Terms

The direction that the singles or ply twists matters as you add additional structure to the yarn. **Twist,** in yarn, is typically **described as "Z' twist or "S" twist**. Thus, relative to how you are looking at the yarn, does the winding look more like a Z or an S. This twist makes a difference in how the more compound yarn structures are formed, and also can be leveraged in processes of weaving, where the twist structure allows fabrics to take on three dimensional properties. 

Yarns are also created by building up and around other yarns and structures. Smaller yarns make bigger yarns etc. In general, there are two parts one can design in a yarn: **a core** and **a sheath**. Some yarns are consisting of a core and have no sheath. Their structures are solid \(no hollow\) and all the fibers wrap, meaning nothing consistently through the center of the structure. Some yarns are **core-spun**, in which a braid or ply is created as a sheath outside of a single and central core material. Others are hollow, in which the filaments and fibers are twisted around an empty core, allowing you to potentially insert something and have it be completely covered by the sheath. 

### **Plying**

The first technique we'll cover is plying. Plying consists of twisting multiple singles together. You can make cores and core-spun yarns using plying, but you cannot make hollow structures. You can ply with 2, 3, or however the hell many yarns you like, but its probably best to stay on the small side \(under 6\) to keep structure if you are doing this somewhat freehand. For bigger yarns or projects, you'll often see plies of plied yarn which are technically called "cabled" yarns. This is a yarn that is made by plying together previously plied yarns. 

If you want to ply yarns together, here is what you do. Each of the singles strands is twisted in one direction \(lets say Z twist\), independently of the other. Once they are all twisted to the desired angle the counter-acting twist is applied from the joined end in the opposite \(or in this case S-direction\) and propagates through the singles, joining them together.

The best video I found demonstrating this process comes from a demonstration of medieval rope making. This shows how six plys are twisted in unison and come together to form a solid yarn/rope as a core. 

{% embed url="https://www.youtube.com/watch?v=toyOKOi0DsM" caption="Good demonstration of plying with 6 strands involving equipment traditionally used to make ropes. " %}

Different equipment allows for different qualities and lengths of yarn to be produced more easily. Here are some techniques you could use or investigate: 



#### Plying on a Spinning Wheel

If you were an elegant and details oriented spinner you would likely ply using a spinning wheel. This has the advantage of creating long lengths of consistently \(with skill\) plied yarn. The downside is that it requires a spinning wheel which you may not have. 

{% embed url="https://www.youtube.com/watch?v=ibpaZXq1eiU" caption="Video demonstration of plying two singles using a spinning wheel. This allows for consistent twisting along very long lengths of yarn." %}

You can also create core-spun yarns using a spinning machine by plying or [adding fibers directly from top or roving around a solid and continuous core](https://www.mybluprint.com/article/core-spinning-yarn). This solid core is a useful structure when you want something to be fully encased in a fiber and/or when your core has very different material properties to your fibers. 

#### Spinning with A Drop Spindle

A drop spindle provides a more accessible way of creating long-ish lengths of consistently spun yarn but also requires a bit of practice. [Anne-Marie Lavigne](http://emeteuz.com/woven-signals) shows us how this comes in hand when we need to make long lengths of our own conductive thread:

{% embed url="https://vimeo.com/93086189" %}

In this video, she is hand spinning heating wire for activating thermochromic pigments on yarn. By spinning the materials together \(instead of ironing a heating element on the back of the fabric\) she's ensuring there is really good transfer between the yarn and the heating element. As we found in our own studies, any air that comes between these two can drastically extend or reduce the activation time for the yarn to change color.

If you want to get a feel for this, take any string or yarn you have nearby, twist it as much as you can between your hands and then fold it, holding the two ends in one hand and the fold in the other. You can watch the ply twist into itself to achieve balance, and if you feel like it, you can help it along and see even more twist.  

![The steps of plying with the drop spindle.](.gitbook/assets/compound-image.png)

#### Ad Hoc Setups 

And if you were a bit more hasty or resource constrained you could follow each of these techniques. Both are a bit limited in the sense that you have a fixed length to work with. 

This Instructables demo shows a nice contraption for plying a variable number of yarns together. Ideally, the yarns would be equally spaced along the outer edge of a circle but this seems to get the job done for a proof of concept. 

{% embed url="https://www.instructables.com/id/Conductive-Thread-Wind-up/" caption="Instructables Link for DIY Plying Set Up" %}

This video uses a drill, because it will go super fast \(but I think maybe too fast to be helpful\) and does a nice job of creating an even spacing between the hooks. The result however, is very inconsistent likely as a result of lack of experience and, I imagine, the fixed end point of all the yarns. Now if you wanted your rope to ply around a solid core, you could basically add a fourth "core" yarn directly in the center of the other three. This yarn would not twist with the others, and if you kept it at tension, the other yarns would start forming around it when relaxed. 

{% embed url="https://www.youtube.com/watch?v=2kQBp\_5PPTc" caption="A video demonstration of a home-made setup for plying 3 yarns together using hooks and a drill. The resulting wire is not of very consistent quality." %}

I tried to make my own heating yarn using an Incredible rope machine,  which allows you to ply size strands together. I added in magnet wire and mercerized cotton for the strands and it was really tough \(because I couldn't keep tension\). In hindsight, I think some of the challenge was that I tried the use yarn that was already plied \(2-ply\) so the yarn's own twist might have made the structure unravel. It came put something like this: 



![Copper magnet wire \(~32AWG\) and cotton rope. ](.gitbook/assets/rope_1.jpg)

### Braiding 

Braiding is a technique that uses coils multiple strands, in different twist directions around a solid or hollow core. Industrial braiding uses a machine called a "[maypole machine](https://www.youtube.com/watch?v=SKHuZEhrQ2E)" that is utterly fascinating to watch. Braiding is often used for creating sheaths around a core. What is nice about braiding is you can have a core that is a completely different material than the sheath without having to wrestle with too many different issues in tensioning. I have never worked with an industrial braiding machine, but making braided tubes by hand has opened up a lot of possibilities for experimenting with integrating many different materials. 

![A kumihimo wheel, yarns and resulting rope ](.gitbook/assets/kumihimo_1.jpg)

Braiding machines have yet to enter the DIY marketplace \([and this one is out of stock!](https://www.kickstarter.com/projects/mixedmediaeng/rope-omatic)\), but we can create small samples at least using a technique called **Kumihimo.** Kumihimo braiding is a technique in which several lengths of yarns are braided into hollow tubes. Kumihimo templates can be used to create braids with custom textures and patterning. The templates are easy to produce in cardboard on a laser cutter at various thicknesses. During this braiding, the maker has more control over tensions than they might with techniques that spin yarns together, thus, they may be ideal for applications that require brittle materials to be integrated into the outer structure of the yarn. It is also nice because it can adapt to several different numbers of individual yarns composing the braid. If you want to braid around a core, you simple pace your core material through the hole in the center and while you are braiding, it will wrap around that core on its own. A special thank you to [Pamela Liou](https://pamelaliou.com/) who was the first to introduce me to Kumihimo. There are many [patterns available online](https://prumihimo.com/resources/braiding-patterns/) that allow you to create braids with different cross sections ranging from square to semi-circular. 

### I-Cords

One final structure that may be useful, and it at least easier to prototype is a knitted i-cord. This structure is hollow with a knitted sheath. Unlike the other two structures, this sheath is quite stretchy. The downside is that the yarn will be a bit fat \(by yarn standards\). The structure can be created by [hand techniques](https://www.youtube.com/watch?v=dfkFRa9tjns) or with wonderful little contraptions like and [embellish-knit ](https://www.studioknitsf.com/embellish-knit-cords-power-tools/)hand cranked i-cord maker. Traditionally used to make little pulls, like the ones on a hoodie, they can also be useful in creating yarn-like structures. When working by hand, you have much more flexibility with the materials and sizing of the cord. With some finessing, you can feed the machine \(or a hand knitter\) both conductive and non-conductive materials at the same time to create a conductive cord structure. This structure has been really useful for acting as a pull or strain sensor, or, when tied around my ribcage, makes a pretty robust breath sensor. The measuring works through resistive sensing. The knitting structure basically maximizes the length of the conductive thread. So when the cord is strained, it strains all fibers of the conductive yarns, tightening their structure and lowering the overall resistance.  

![Feeding two materials into the Embellish-knit machine at once to create a conductive sheath. ](.gitbook/assets/2017-12-19-14.07.00.jpg)



![Knitted I-coord with wool and conductive sheath. ](.gitbook/assets/knit_2.jpg)

Because of the hollow structure, it is also possible to add a cord within the sheath. I have found  it most useful to add this core at the time of knitting, rather than trying to feed it through after. In one project, we used conductive materials in the core AND the sheath to create a string that [would know something of its own shape](https://dl.acm.org/doi/10.1145/3170427.3188570). It did so by .adding five different insulated conductive wires inside the structure. Each insulated wire was then attached to a exposed conductive "ring" made of copper tape. This allowed us to take resistance measurements at five different points along the length. Depending on which sensors showed changes in resistance and which didn't, we could tell which regions of the string were crossed.

 

![Diagram of the yarn-based system.](.gitbook/assets/paperdiagram%20%281%29.jpg)

![Measuring setup. A power and ground connection at the beginning and end of string. A non-conductive section in between these regions makes resistance is measured across the entire length of the yarn.](.gitbook/assets/2018-01-03-14.43.49%20%281%29.jpg)

![Resistance reading with no crossings in the yellow region](.gitbook/assets/2018-01-03-14.47.43.jpg)

![](.gitbook/assets/2018-01-03-14.48.15%20%281%29.jpg)

### Summary

Each technique has its strengths and weaknesses. The string figure sensor could have been made with knitting, braiding or plying, though, knitting provided us the best way to integrate our core most quickly. In other cases, you may especially need one technique more than the other. For instance, the knitting structure \(I think\) is the only one that could give us the quality of breath readings we needed because of its ability to stretch and place tension on long lengths of conductive yarn. For McKibben muscles, you must have braids made of material that "slides" well on itself so it can dramatically change its diameter when compressed. 

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

