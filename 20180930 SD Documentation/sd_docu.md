# Suspended Desire Machine Documentation

### Information    
* Title: _Suspended Desire Machine_
* Category: _Semester project_
* Student: _AL_
* Course Title: _Sonic Theories, Sonic Art Practices: Unlimited_
* Lecturer: _PK_
* Year: _ST 2017_


### Table of contents
* [Description](#description)
* [Abstract](#abstract)
* [Concept](#concept)
* [Process](#process)
* [Technical](#technical)
* [Conclusion](#conclusion)
* [Collection of media](#collection-of-media)

## Description

A membrane separates _a_ from the rest of the world. That's the story of the Suspended Desire Machine. _a_ is constrained, someone put in a box. _a_ cant do anything. Except waiting. It waits for you, to turn it on, to be turned on. Take a seat, hit the switch. Watch. Closely. Don't touch. Leave it running, if that's what you desire. The Suspended Desire Machine is not a furniture, it's a factory.

## Abstract

## Concept

### Houellebecq

In an uncanny way I am an admirer of the French author Michel Houellebecq. I would never consider myself a fan of anything, but in his case I would admit I get quite enthusiastic about each new book. The fiction of Michel Houellebecq actually interests me because there is much to reflect upon. Here is why. The characters in Houellebecq's novels are exclusively white males of mid age with an dispirited attitude towards their impotent existence. They urge to compensate this discrepancy by excessive outgrowths of their mostly burdensome traits. The novels are written in a state of prosperity in Western and Central Europe where for a share of the demography the only glass ceiling that is left is the nihilistic confrontation with their own transience. No values left to believe in and nothing to do. They live and die alone. Therefore the characters in Houellebecq's novel consequently develop some cringeworthy habits. Worth mentioning that a lot of these habits have to do with sexuality, which is the context of my work. Occuring examples would be swinger clubs or sex tourism. I was interested in another practice though that I am going to explain later.

### Žižek & Lacan

While I was conceptualizing an idea for the seminar to work on I was also reading a book about Jacques Lacan by Slavoj Žižek ("How to Read Lacan"). I learned about a concept called the Big Other. Lacan would abbreviate it as "A" since he is a constant user of algebraic notation. The Big Other can appear for example in the shape of god, the law or societal expectations. Generally these are topics we perceive to be of an almost metaphysical validity. Therefore Lacan uses the term "other" in Big Other, because we tend to situate these concepts in an realm outside of our control. But Lacan was a psychoanalyst and very well aware that the distinction is only imaginary. We might be able to look at society as an emergent feature but still it is immanent to human behavior as such and arises from human psyche. What does that mean? We experience the Big Other as something separate then what we experience as "I" and we are in a constant dialog with it was we are negotiating our terms of being. The Big Other only alters itself through value shifts in society and not by individual contemplation but still can only be split from the rest of the psyche conceptually by outside observers (psychoanalysts). Eventually this means that all the societal and social fears we have are created only by the individual itself through negotiation with the Big Other, even though the expectations that will lead to fears are coded into the Big Other through society.

After reading it for a couple of times this concept stuck with me and formed a picture that serves as an analogy. I was thinking of a membrane that separates both spheres from each other, the "I" and the Big Other, yet through its elasticity both form one shape together. A change in the medium on one side of the membrane will affect the medium on the other side indirectly and inevitably. Both are separate but one.

### BDSM

While studying Houellebecq again I found his depiction of the BDSM culture quite interesting. Houellebecq himself states that he finds sadomasochistic practices both physically and morally disgusting. But his characters tend to have another opinion. Some of them would suggest that sexuality as a social institution will find it last step in a Sade-like system or that BDSM is only a subcultural surrogate for conventional "vanilla" sexuality. In the novel "Platform" though a protagonist makes a profound observation while being in a BDSM club with a couple of rubber fetishists. Wearing latex, the more the better, puts an artificial buffer between humans so skin doesn't have to touch anymore. It's almost not like there is a medium in between the bodies because latex is some form of a new skin. The rubber is tight and elastic so it follows the surface of the body perfectly. There is an artificial separation between human bodies in the practice of rubber fetishism. Instead of skin touching skin there is something that takes over the act of applying physical forces to each other which strongly reminded me of the idea of the membrane I developed before.

As sexuality also is part of the Big Other and arises from expectations I found this coincidence to be quite intriguing thrilling to think about. Even though I didn't even want to make an attempt into forming a consistent theoretical concept out of my vague ideas it served as a starting that was interesting enough for me to investigate this further through artistic practice.

## Process

### Sex robot

I had an idea of a membrane made from latex which I wanted to investigate with this work. The membrane should have been mounted on a construction made of steel beams, similar to the structures just in BDSM practices. So there would have been a surface that could be modulated through applying forces locally, hence changing the tension and the curvature. As artificiality was an integral part of my concept I got the idea to incorporate robots into the installation that I had in mind. I imagined a huge sheet of latex stretch over a couple of robot arms that poke the latex from beneath.

So I went into fabricating latex sheets, because they are quite expensive, which was quite a smelly experience, and I started thinking about robots. I came up with a structure that uses two motors on a base axis and provides two degrees of freedom on a polar coordinate system. The kinematics are based on a parallelogram and enabled me to come up with a simple design that I could easily prototype with PMMA, a couple of screws and laser cutting. I never really worked on robotics before but this architecture was quite manageable for me. So I started developing a prototype software for the inverse kinematics that I needed to animate the robotic movement. Instead of telling each motor how to move the software should be able to receive a point in two-dimensional space and move the motors in a way so that the arm moves to that position.

The next step would have been to write an animation software that lets the effector (tip of the robot arm) follow predefined splines. I programmed something similar later on, but not for this robot. Instead I invested some time in something like a case film for the existing robot prototype and then dismissed the idea completely.

### Video of work in progress

[![Robot WIP documentation](images/thumbnail.png)](https://www.youtube.com/watch?v=E3HFKed5_sM)
_Please click on the image to see the video._

### A speculative approach

I had a couple of difficulties with the material. Under constant tension homemade latex is is nice for a couple of days but begins to rip and lose its shape pretty fast. Out of precaution I changed the installation so that there is no requirement for latex anymore. Instead I wanted to use fabric. Out of some desire I can't recall anymore I had the urge to make a product. Not a commercial product, but something that could be reviewed in the context of speculative design. So I changed the concept from an open installation that exposes all hardware and technology to modernistic simplistic shape that hides all complexity and technology inside itself and only interacts with the outside world through the membrane. I made a white cube. As I wanted to see the installation as a product I used the analogy of furniture to situate the piece. In the beginning I thought of something like a stool or a table but soon realized that it would also be a viable approach to hang the cube from the ceiling like lamp and use a light switch to turn the installation on and off. I imagined that it would be nice if the user (visitor) would be able to sit beneath the object to get some kind of esoteric treatment. For this part I again made use of a concept by Žižek, something he calls _interpassivitiy_.

## Technical

### The box (aka COX)

For building the robot I actually made quite some effort to get the installation to a level finishing were it is comparable to an actual retail product. This means I had to hide every visible trace of human influence in manufacturing. In the end the installation was a wooden box with a perfect white finish, a suspension on four metal wires and the interface. The interface firstly consisted of a gray textile cable with a switch that was mounted on the box with a strain relief. Because the robot should always be in standby and not turned off, when the switch is off, I had to hack the cable and switch so that the switch always conducts but sends a digital signal to the robot when it should turn off. The second part of the interface was the membrane. It was mounted through a quite sophisticated frame directly on the cube so that the membrane looked like the cover of a hi-fi speaker. The problem at this point was that the cover sits on the only opening of the box which means it had to come off quite fast in need of repair but still had to look good. I claim that I managed to solve this problem quite well.

### The robot

## Conclusion

Technology very well hidden

## Collection of media