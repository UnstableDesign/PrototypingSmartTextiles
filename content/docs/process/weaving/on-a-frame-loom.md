# Frame Loom Weaving

As you might expect, hand threading a yarn over and under every row can be tedious, which has given rise to the development of horizontal looms with **heddles**, or, contraptions that lift the warps for you.  The heddles lift the yarn, and the weaver throws the yarn through the opening, or **shed**, lowers the heddles and beats the row they just laid to meet the fabric. The particular selection of heddles on any given row are called the **pic**. If you are looking to learn, [Peggy Osterkamp is the go to source for learning](https://woolery.com/weaving-for-beginners-an-illustrated-guide.html?nosto=categorypage-nosto-1). Many heddle based looms consist of the use of frames \(which contain sets of heddles\) and treadles which easily allow different frames to be lifted in combination with one another. 

![](..//loomstructure.jpg)

#### Weaving on a Rigid Heddle Looms

Rigid heddle looms often have one frame, making it easy to quickly weaving tabby and inviting the weaver to play with other hand techniques integrated with the tabby. 

**Frame/Shaft Looms**

Frame or Shaft looms are made to fit on table tops or floors and can have 2 to as many as 24 frames, depending on the loom. Frame looms also come in a variety of widths. When warping, the weaver threads each frame with a particular sequence of warps \(most simply, a "straight draw" which takes every 1st warp and puts it on frame one, every 2nd on frame two, every 3rd on frame three \(and so on\). To create a pattern, then, one "lifts" the frames that give them their desired pic. The lifting is done by hand or by the use of treadles, foot pedals that attach to different sets of frames allowing you to select them. Frame looms make it easier and faster to produce repeating patterns. Some frame looms are computer controlled, allowing motors to lift the frame rather than pedals. These are often called dobby looms. The loom shown in the image above is a 8-shaft Floor Loom. Further specifications \(e.g. jack loom, countermarch\) describe the mechanisms that raise and lower the heddles \(and often make it physically easier to do so, especially with large numbers of shafts and or wide widths\). 



**Frame Loom Draft:** 

![](..//screen-shot-2020-08-13-at-8.47.03-pm.png)

This is a draft that I created for my frame loom that shows the primary units that repeat across the width of the fabric. To help with my process, I use non-white to represent any area where the Weft travels UNDER warp, but different shades to different colors of material. The resulting material looked like this \(horizontal is the length/warp\). What is interesting to note is that every section of the weave was created by components of this draft, but that changing materials in both the warp and weft really create the visual pattern. It is also good to reming yourself that when you weave, it will not be square like your draft, thus, you often have to make adjust your draft to what "square" means in your draft. For instance, in the weave below a square was composed of about 20 warps and 30 wefts.  

![](..//61375229703__193e5c94-3e8b-458d-acd7-723925605427.jpg)

Yet, above I cropped the most important part out of the picture, which is the part of the draft that represents how to thread the frames, tie up the frames to the treadles, and shows the treadling pattern. If you need a refresher on how the loom works, you can reread the process section for [weaving on heddle-based looms](). So now here is the full picture: 

![](..//screen-shot-2020-08-13-at-9.08.15-pm.png)

The top left shows the tie up, the top row shows the threading, and the left shows the treadleing. The grid in the bottom right, shown before, is called the draw down. 

**Interpreting a Draft**

First of all, if you have time, you are free to ignore all the other business and follow the pattern in the lowest and rightmost grid and simply do all the over/undering by hand. So the first row would be over 1, under 1, over 1, under 1 and on and on. The next would be over 1, under 1, and so on. 

If you have a loom with heddles, it will save you immense amounts of time. As such, when you would go to make this pattern on your loom, you would begin with the threading, threading each warp through the frame indicated by the grid. So on this draft, you would thread the left-most warp to the 6th frame, the next to the 5th, the next to the 6th, then the 3rd, 4th, 1st, 2nd, and so on and so forth. Typically, the "first" frame is the one closest to the fabric beam or the front of the loom and they are numbered successively from front to back. Another explanation can be found here: [https://weavingspace.co.uk/blog/threading-draft/](https://weavingspace.co.uk/blog/threading-draft/)

When you are done threading, you would then work on the tie up \(if you're loom has pedals, otherwise you might have to select these frames by hand on each row by raising and lowering levers that raise and lower frames in different combinations. The tie up, thus, represents which frames need to be lifted in any given pic to achieve your desire pattern. So from left to right, I would start by tying frames 1, 2 and 6 to the first treadle. Then I would tie 3,4, and 6 to the next treadle. Then 2, 4, 6 to the next, and 1,3,5 to the last. You can find additional details here: [https://weavingspace.co.uk/blog/reading-a-tie-up/](https://weavingspace.co.uk/blog/reading-a-tie-up/)

When you sit down at the loom to weave you refer to the left most grid to understand the treadling. This is the order in which you push the pedals \(or lift the levers\) in order to get the pattern represented in the lowest and right most grid. Put another way, it represents the specific pics that have to be repeated to obtain the structure. Here is another explanation: [https://weavingspace.co.uk/blog/treadling/](https://weavingspace.co.uk/blog/treadling/)

#### 

#### Writing a Draft

Sometimes you know the structure you want, but not the machine settings to obtain that pattern. Or you have a textile you want to mimic, but you don't have the draft at all. You can do this by first looking very very closely at the fabric and manually marking the draw-down where you note over and unders. Some people photocopy their fabric and enlarge it to make this simpler, or take apart the fabric row by row to understand the order of threads and over/unders. 

I think the Weaving Space blog offers a nice tutorial on a way of [doing this that is more germane to weavers](https://weavingspace.co.uk/blog/how-to-turn-a-profile-draft-into-a-threading-draft/) but I tend to approach it like a computer scientist. Once you have the draw down you follow an algorithm, told in pseudo-code below: 

* For each column c in the draw down 
  * Look at all the cells  in c and represent the sequence from top to bottom as a bitstring \(e.g. 0 meaning white, 1 meaning black; sequence reading as \(0, 1, 0, 1, 0, ......, 1\)\) 
    * if this if the first column OR the bitstring is DIFFERENT from one you have seen previously:
      * assign it \(fill in the cell\) in the next unused frame in the column c on the above threading pattern. 
    * if you have seen this pattern before
      * assign it \(fill in the cell\) of the column c in the above threading pattern in the same frame row that corresponds to the column of which the pattern is a repeat. 
* For each row r in the draw down
  * Look at all the cells in r from left to right and represent the sequence of cells as a bitstring \(e.g. 0 meaning white, 1 meaning black; sequence reading as \(0, 1, 0, 1, 0, ......, 1\)\) 
    * if this if the first row OR the bitstring is DIFFERENT from one you have seen previously:
      * assign it \(fill in the cell\) in the next unused treadle column in the row r on the  treadling pattern to the left. 
    * if you have seen this pattern before
      * assign it \(fill in the cell\) of the row r in the treadling pattern on the left in the same column that corresponds to the row of which the pattern is a repeat. 
* For each row r in the treading pattern;
  * scan until you find the column that is assigned to this row, call that c
    * look at the draw-down for row r, for each cell in r of the draw-down;
      * if the cell is white, do nothing
      * if the cell is black, locate the assigned threading frame row f that corresponds to that draw down cell, and color the cell at row f and column c in the tie down black.  


# How to Weave on Floor Loom

## Anatomy

Below is the anatomy of a floor loom. 

![image](/floor-anatomy.png)
![something](/warp-weft-anatomy.png)


The loom consists of several parts. More details about each part can be found in the key terms section.


## Basic Mechanics

![](/treadle-label.jpg)
![](/shaft-label.jpg)

[1] There are multiple treadles on the loom. There are multiple shafts on the loom. 

![](/treadle-tieup.png)

[2] The treadles can be tied up to as many shafts as the weaver desires. The tie up connects the shaft to the treadles so that the weaver can control which warp is raised and lowered


![](/treadle-shaft-tieup.png)

[3] Pressing on the treadles tied to the shafts raises the warp creating the shed


![](/shaft-raise-label.jpg)
[4] The treadles can be tied up to as many shafts as the weaver desires.



# Floor Loom Process Overview

![](/floor-process-diagram.jpg)


# Warping


__Synopsis of Warping Process:__
1. Measure the warp
2. Tie the Cross 
3. Attach warp to the back apron rod
4. Insert Lease Sticks
5. Thread the heddles
6. Sley the reed
7. Tie the warp to the front apron rod
8. Tie up treadles

__Step 1: Measure the Warp__

![](/warp-board.jpg)


[1] Gather two bobbins of thread that are contrasting colors. Then, find a warping board and hang it such that you can access the pegs easily. 


![](/tie-loop-warp.gif)
![](/loop.jpg)


[2] Start with your first colored thread. Create a slip knot in one end of your thread and place it around the first peg. This will be the start of our guide thread. 


![](/warp-end.png)
![](/warp-direction.png)


[3] Then, wrap the thread along the warping board by following the image above and secure it on the final peg with another slip knot. This thread will guide where you wrap your warp threads.

[Chandler 56](https://www.google.com/books/edition/Learning_to_Weave/T4BIEAAAQBAJ?hl=en&gbpv=1&printsec=frontcover)


![](/guide-string.png)

[4] Next, we are going to follow the guide string to add to the warp. This includes making a cross around the final two pegs. The cross is a figure-eight path around the final two pegs which will be helpful for string management later on. The left image shows the cross in context of the entire warping board. 

[5] The right diagram shows how thread is taken around the final pegs to create the cross. When you reach the final two pegs, you will take the warp thread over the second to last peg, under and around the last peg (#1), and back under the second to last peg (#2) to meet the thread you brought again on top of the third to last peg (#3).
)


![](/warp-gif.gif)
![](/warp-first-row.png)

[6] The video and illustration show adding a warp thread to the board with a cross

[7] When you reach the initial peg again (as shown by step 4 above), you will repeat this motion until you have measured 12 threads of this first color. 

[8] To get 12 threads, you will travel from the first to last peg and back, counting a new thread each time you reach an ending peg. EXAMPLE: starting on the first peg, you travel along the board until you reach the end of the cross. That is 1 thread. Then, after making the cross you travel back to the first peg. That is the 2 threads. You can check your progress by counting the number of threads on top of the second to last peg and multiplying it by two (half of the threads will be over the cross and half under). 


![](/counting-thread.jpeg)
![](/counting-threads-label.jpeg)

[9] Once this first section is complete, you will tie a counting thread on the warp which is used to lay threads in the correct order on the loom later on.


[10] Tie the counting thread on this bunch of thread so that it will secure that bunch together but you can also take it out later on. A half knot will suffice. See on the right image how that same counting thread will be secured to the next bunch as well, so make sure to cut enough to span the width of your warp.


![](/cut-warp.jpeg)
![](/retie-warp.jpeg)
![](/tie-warp.jpeg)


[11] Next, you will need to grab the second color you picked so that you can use if for your next stripe.
[12] Begin by cutting the end of the first color about an inch or two past the end of the peg and tie the second color to it.

![](/warp-2layers.jpeg)
![](/warp-2.jpeg)
![](/counting-thread.jpeg)


[13] With this second color attached, measure 12 threads again just as before.
[14] When finished, tie the tails of the counting thread from the first stripe around that inch of warp you just made with the second color

![](/warp-final.jpeg)
![](/warp-final-close.jpeg)


[15] Then, cut the end of that second stripe, and re-attach the first color to the end just as before. Measure 12 threads with that color.


[16] Continue this process until you have 10 total stripes, 5 of one color and five of the other color

__Step 2: Tie the Cross__

![](/tie-cross.jpeg)


[1] Now that you have all your warp, you want to secure it before moving it over to the loom to ensure that the threads stay in order


[2] To do so, we will tie a string around 5 areas: the top and bottom of the loops on either side of the cross and around the intersection of threads themselves. Begin by tying string around the loops as seen above. Again, you will eventually untie these, so make sure they are secure enough to hold the threads, but loose enough to get undone



|      |   |
| ----------- | ----------- |
| ![](/cross1.jpeg)     | ![](/cross2.jpeg)      |
| ![](/cross3.jpeg)  | ![](/cross4.jpeg)       |

[3] Next, you will tie the middle of the cross. Begin by taking a string around the back of the cross so both ends are facing you

[4] Then, wrap one end of the string back through the loop and around to the front on the other side.

[5] Tie the two ends together to make a half knot


![](/finsihed-warp-labeled.jpeg)

[6] Now, double check that your counting threads are all tied properly and tie one more piece of thread around the middle of the warp

![](/start-tie-warp.jpeg)

[7] Finally, tie the top and bottom of the starting loop just as you did the loops of the cross.

__Step 3: Attach Warp to Back Apron Rod__

![](/remove-beater.gif)

[1] Begin by lifting the beater out of the loom by taking off the rail and reed so that you can easily access the shafts.


![](/open-shafts.jpeg)


[2] Slide all heddles on the shafts to the sides so there is a clear space between them


![](/warp-on-loom.jpeg)
![](/warp-on-loom-front.jpeg)

[3] Place the warp along the loom by wrapping the cross end around the front beam and guiding the rest of the warp to rest on the back beam


![](/warp-front-beam.jpeg)
![](/apron-rod.jpeg)

[4] Pull the apron rod up to the end of the warp on the back beam, slide the warp over it, then tighten the apron rod slightly with the crank on the left of the loom. We will spread the warp out next, so make sure to leave a little slack


![](/spread1.jpeg)
![](/spread2.jpeg)


[5] Spread the warp out on the apron rod into even bunches. We have 120 total threads and want to spread the strings out in 4 equal sections. So, we spread 30 strings into each section (designated by the white ties holding the apron rod to the warp beam). Therefore, in each section there are 2.5 of each color block.  


![](/spread3.jpeg)

[6] Remove the counting tie, then continue spreading the warp into these equal sections along the apron rod.

![](/spread4.jpeg)


[7] Make sure to be meticulous in this process, we want to make sure all strands are laying in the right order and flat on the apron rod

![](/spread5.jpeg)
[8]  With the apron rod set, move to the front of the loom and tug on the warp at the cross end to create tension across the warp.

![](/spread6.gif)

[9] Work from front to back to ensure that all the threads are in order and laying flat


![](/spread7.gif)
[10] Once you feel like the threads are nicely lain, you can crank the back beam to tighten the warp across the loom


__Step 4: Inserting Lease Sticks__

[1] Gather some thread and tie two loops around the top rail of the last shaft, closest to the back beam. Spread them out to about the length of the lease sticks. This is where your lease sticks will be held. See on the left side how this thread will hold the lease sticks when they have been set.


![](/lease1.jpeg)
![](/lease2.jpeg)

[2] Gather the lease sticks and place one on either side of the cross. Tie the ends of the lease sticks together so that they cannot fall apart off of the warp.

[Eugene Textile Center](https://www.eugenetextilecenter.com/ashford-table-loom-lease-stick)


![](/lease3.jpeg)

[3] Slowly shimmy the lease sticks back, pulling the cross closer to the back beam. When you pass through the final shaft, loop the ends of the sticks in the hanging thread to secure. At this point, you can cut the ties around the cross as it is secure now.


__Step 5: Threading the Heddles__

![](/measure-warp-cross.jpeg)

[1] To thread the heddles, begin by winding the warp in so that there is only 8-10 inches reaching out past the first shaft.


[2] Slide 30 heddles from each shaft (total of 120 heddles) over to the right side of your warp. These will be the heddles you thread.


![](/show-heddles.jpeg)

[3] We are going to thread a straight draw. Starting on the very far right most warp thread, we are going to take the first thread through the 4th shaft, the second thread through the 3rd shaft, the third thread through the 2nd shaft, and the fourth thread through the 1st shaft. Then, we repeat this process for the rest of the warp so that the threads are threaded in the pattern 4,3,2,1 all the way through.


[4] Begin by pulling the first four heddles out to the right of the warp. They should be in the order 4,3,2,1 as shown above


![](/thread1.jpeg)
![](/thread2.jpeg)

[5] Now grab the first color of warp and cut the loop at the end so all the threads are even


![](/thread3.jpeg)
![](/thread4.jpeg)

[6] Thread the newly cut warp through the heddles as described in step 3 above. To reiterate, the furthest right thread will go through the 4th shaft heddle, the second to last warp through the 3rd, and so on through the 1st shaft heddle. After each color block is threaded, tie all the warp threads together in a slip knot to keep them threaded and out of the way.


__Note:__ heddles have directions, so make sure that the warp thread travels straight through from the back beam to the front. You can figure out which way is correct by threading multiple ways.


__Step 6: Sleying the Reed__

![](/sley1.jpeg)
![](/sley2.jpeg)

[1] Next we will sley the reed, meaning that we will bring the heddle threads through the reed. Begin by replacing the reed on the beater (remember we had removed this back when laying the warp down).


[2] On the right hand side of the beater arm, there is a pin used to secure the beater in place. Make sure to secure this pin before starting to sley.  

![](/sley3.jpeg)

[3] Once the beater is set, release the warp so that there is 8-10 inches of warp that can come out past the beater. Now we are ready to sley.



![](/sley4.jpeg)
![](/sley5.jpeg)

[4] Grab one section of color, untie the slip knot, and separate out the last four threads on the right hand side of the warp.

[5] Spread the four threads out in your hand and bring forward over the beater


![](/sley6.jpeg)

[6] Now, measure the length of the reed. The floor loom reed is 26” long and we have 10” of warp. So, we will have 16” of warp leftover when finished sleying. That means we want to start the warp 8” from the right hand side of the reed so that our warp is centered on the reed.



![](/sley7.jpeg)
![](/sley8.jpeg)

[7] With the first slot in mind, pull those first four threads out and use the sley hook to grab the furthest right thread and pull it through the dent you identified to be 8” into the reed


[8] Repeat this process with the rest of the threads in your hand, placing each new thread in the next dent over from the first. It is easy to skip a dent or place two threads in one dent, so double check you are placing only one thread in each along the way.


![](/sley9.jpeg)
![](/sley10.jpeg)

[9] Continue sleying the rest of the color block that you are on. When finished with a block of color, tie another slip knot to keep all the colors together.


![](/sley11.jpeg)
![](/sley12.gif)

[10] Repeat this process until all the warp is sleyed. On the left, you can see what the threads look like as they are placed through the dents and tied with a slip knot. On the right you can see how to grab the thread with the sley hook from your hand and pull it through.


__Note__: it is helpful to have a small loop in the thread being slayed for the sley hook to grab on to

__Step 7: Tie the Warp to the Front Apron Rod__


![](/tie1.gif)
![](/tie2.jpeg)

[1] At this point, the reed is completely sleyed.

[2] Release the front beam from the lock and lay it back against the loom


![](/tie3.jpeg)
[3] Next, pull the front apron rod up and over the front beam.


![](/tie4.gif)
![](/tie5.jpeg)

[4] Begin tying the warp onto the apron rod. To do so, split the section of warp into two pieces and wrap around the apron rod by first taking the warp thread over the rod towards yourself and then back under the rod toward the loom. Then, tie the two ends together loosely. This will allow you to easily adjust the tension


[5] Repeat this process for all warp sections until all of them have been tied on the apron rod.


![](/tie6.gif)
[6] Adjust and re-adjust the knots until there is even tension across all of the sections of warp. Once even tension is achieved, double knot each section to secure.



__Step 9: Tie Up Treadles__


![](/treadle.jpeg)
[7] The last step to set up the loom before getting to weaving is tying up the treadles. You can vary your woven piece quite a bit by changing the treadle tie up. Make sure to look at your draft to determine the treadle tie up for your desired piece. If you are unfamiliar with a draft, see the next section to learn more about each component.



## Threading

Variation in threading patterns provides opportunity for different weaving patterns. Threading variations are unlimited, but families of weave structures or patterns are produced from particular threading.  (Chandler 113)


In this tutorial, we threaded a straight draw. This means that the threads are placed in the following order: shaft 1, shaft 2, shaft 3, shaft 4, repeat.


There are many other ways to thread, see resources here: [Learning to Weave](https://www.google.com/books/edition/Learning_to_Weave/T4BIEAAAQBAJ?hl=en&gbpv=1&printsec=frontcover)


# Full Draft


## What is a draft?

Drafts are the weaver’s blueprints. The blueprint tells the weaver which combinations of frames/shafts to raise together (tie-up), which order to raise the shafts (treadling), which yarn to throw at each pick (treadling), and what the fabric will look like overall (drawdown).


![](/draft1.png)
[Chandler 120](https://www.google.com/books/edition/Learning_to_Weave/T4BIEAAAQBAJ?hl=en&gbpv=1&printsec=frontcover)

![](/draft2.png)
[Nishizaki](https://observablehq.com/@lemonnish/generate-a-weaving-draft)


## Parts of a draft

__Threading__ - as described above in the warping section, threading tells you what shafts and in which order to thread the warp through the heddles.

![](/thread1.png)
[Booker](https://weavingspace.co.uk/threading-draft/)
![](/thread2.png)

[1] Every row in the draft represents one shaft and every column represents one warp end. The number indicates which shaft each warp end should be threaded on. The numbers in the boxes refer to the shaft number. These can be replaced by symbols or colors.


[2] “Xs” are also a common way to mark threading. The threading diagram on the right lines up to the shaft and warp ends to display what this threading looks like on the loom.


__Tie-Up__ - the tie-up tells you how to connect shafts and treadles. On a floor loom, the shafts are connected to the treadles via a string.

![](/tieup1.png)
![](/tieup2.png)

[1] Treadles are tied to shafts via strings. Each vertical column represents a treadle and each horizontal column represents a shaft. Here, you can see that treadle 1 lifts shafts 1 and 3.  


__Treadling__ - the treadling is the order in which you press the treadles and which yarns to throw at each press of the treadles. 
TODO

__Drawdown__ - the drawdown is a visual representation of what your fabric will look like.
TODO


## Draft Examples

See below several examples of drafts and their woven result. 

__Double Weave__

![](/top-double.jpeg)
Top


![](/bottom-double.jpeg)
Bottom


![](/both-double.jpeg)
Both Layers

![](/double-real.jpeg)
![](/double-real2.jpeg)
![](/double-real3.jpeg)



__Plaid Weave__
![](/plaid.jpeg)
![](/plaid2.jpeg)


__Tabby Weave__
![](/tabby.jpeg)
![](/tabby2.jpeg)

__Twill Weave__
![](/twill.jpeg)
![](/twill2.jpeg)



# Weave

![](/weave1.jpeg)

To begin weaving, gather all necessary shuttles and fill the bobbins with yarn. See process for spinning bobbins below. 

__Note__ You will need to reference your draft for the number of yarns you will need. 

__Spinning Bobbins__


|      |   |
| ----------- | ----------- |
| ![](/bobbin1.jpeg)     | ![](/bobbin2.jpeg)      |

![](/bobbin3.gif)


[1] take bobbin out of shuttle by pulling up on the open end and sliding plastic bobbin off of shuttle’s metal rod


|      |   |
| ----------- | ----------- |
| ![](/bobbin3.jpeg)     | ![](/bobbin4.jpeg)      |

[2] Gather yarn and place about an inch of the end into the hole of the bobbin. This will help keep the yarn attached to the bobbin when we start spinning it.


|      |   |
| ----------- | ----------- |
| ![](/bobbin5.jpeg)     | ![](/bobbin6.jpeg)      |

![](/bobbin7.gif)


[3] Place the end of the bobbin with the string into the left end of the spinner. Pull back on the pointed end of the spinner to make room for the rest of the bobbin, then place the other end of the bobbin into the pointed end of the spinner.


![](/bobbin8.jpeg)
![](/bobbin9.gif)

[4] Spin the yarn on the bobbin by pressing the pedal and moving the yarn back and forth so that it spreads evenly across the bobbin. __CAUTION:__ The pedal is very sensitive! A little pressure goes a long way


![](/bobbin10.gif)

[5] Once the yarn has been properly spun, take it off of the bobbin and place it back into the shuttle for weaving. Make sure to cut the small end of thread that was tucked into the end of the bobbin in step 3 to ensure the thread does not get caught in the  when throwing the shuttle.

## Weaving Process


![](/weavep1.jpeg)
![](/weavep2.jpeg)

[1] Following your draft, raise a selection of warp threads by pressing down on the treadle

[2] When heddles are lifted, they raise the warp threads that are threaded through them, creating a shed. This is where the shuttle is thrown through.


![](/weavep3.jpeg)
![](/weavep4.jpeg)

[3] The shuttle, carrying the weft thread, is thrown through the shed. This adds a weft row, or pick, to the cloth.


[4] A weaver closes the shed (lowers all the warps) and beats, pressing the new weft on top of the previous weft. This pressing packs the weft yarns in the weave


[5] Repeat this process until your piece is at the size you desire. See below demonstration for throwing the first pick 


![](/weavep5.jpeg)
![](/weavep6.gif)
![](/weavep7.jpeg)



[6] Demo for the first pick. For the first pick, leave a little bit of extra thread on the end for finishing purposes later on.


Each pick after this (throwing the yarn and beating it) will look identical, the only difference is that your thread will line up with the edge of your piece at later rows as it wraps from one row to the next.  


![](/weavep8.jpeg)
![](/weavep9.gif)
![](/weavep10.jpeg)

[7] Demo for a pick in the middle. To create a clean edge, try and pull your yarn close to the outermost warp thread after you throw the shuttle.

__Finishing Your Piece__


![](/finish1.gif)
![](/finish2.jpeg)

[1] Your piece is finished! You just threw your last pick and now you are ready to remove it from the loom. First, cut a long lead that removes your shuttles from your piece (about the same length as what you left on the first pick)


![](/finish3.jpeg)
![](/finish4.gif)
![](/finish5.jpeg)

[2] Now, release the tension on the loom by pressing the break release foot pedal (rightmost treadle). This treadle is connected to the warp roller and slowly unwinds the warp, allowing more yarn to come forward for use.



![](/finish6.jpeg)
![](/finish7.gif)
![](/finish8.jpeg)

[3] Now that the warp is loose, cut small portions at a time to release your piece from the loom. Leave a few inches of warp on your piece to ensure the last pick does not unravel


[4] At each cut, make a slip knot to keep the warp from falling out of the beater.


![](/finish9.jpeg)
![](/finish10.jpeg)

[5] Once your piece is cut loose, you should have all of your warp knots tied. Your piece will just be connected to the front apron rod.

[6] Next, you can slide your piece off of the front apron rod. You will have frayed edges that you can then finish. Run the piece through a sewing machine with a straight stitch to ensure the piece does not unravel.


# Key Terms
* __beat/pack:__  action for closing the shed and pressing the new weft on top of the previous weft
* __beater:__  packs the inserted weft yarns down. The weaver can control how hard to beat which affects how tightly packed the cloth will be
* __bobbin:__ the cylinder upon which yarn is wound; placed within a shuttle
* __draft:__  a blueprint telling the weaver/machine which heddles to raise and lower
* __frame/shaft:__ holds a set of heddles through which warps are threaded. Lifting the gram lifts the weft yarns threaded through the heddle
* __heddle:__ wire strips attached to frame that warp thread passes through
* __pick:__ a row of weft that has been thrown across warp
* __shed:__ the space between the raised and lowered warp threads
* __shuttle:__ carries the weft yarn during the weaving process
* __throw:__ action for sending the shuttle through the shed
* __treadle:__ are manually attached to frames and “lift” the threads in the frame
* __warp:__ parallel set of yarns held under tensions along the length of the loom
* __weft:__ inserted into the warm in back and forth fashion

