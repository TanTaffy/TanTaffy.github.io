---
layout: default
title: Project TM01
permalink: /projects/project-tm01/
---

# Project TM01
## Outline

Sim racing is a hobby that I've always been fond of doing in theory, however the barrier to entry has always been ridiculously high in my view, so when I got the opportunity to receive funding from the UKESF to work on projects of my choosing, providing proper justification, there was only one real option for me, to realise a vision I had held for years. 

<div style="display: flex; gap: 15px; justify-content: center; align-items: center; flex-wrap: wrap;">
  <img src="/assets/images/prices1.png" width="48%">
  <img src="/assets/images/prices2.png" width="48%">
</div>

### Even now, with significantly increased competition in the market as opposed to years prior, prices for Formula/GT-style wheels are very inaccessible for many people.

## Research

First starting with research on contemporary wheels and their designs/layout, I mainly shifted my focus to GT3-style wheels and adjacent designs. I felt they had the best mix of the yoke shaped wheel while still being simple enough to replicate in a first run at designing a wheel. One wheel that stood out to me in particular was the Fanatec CSL GT3 wheel (formerly the McLaren GT3 V2), primarily for aesthetic reasons with a very 'standard' design, which ended up being the wheel i based initial sketches on, which becomes clear from initial screenshots of my model.

<div style="display: flex; gap: 15px; justify-content: center; align-items: center; flex-wrap: wrap; margin-bottom: 15px;">
  <img src="/assets/images/mclarengt3.png" width="48%">
  <img src="/assets/images/ppwheel.png" width="48%">
</div>

<div style="text-align: center;">
  <img src="/assets/images/tcrwheel.png" width="70%">
</div>

### A sample of the images I referenced for my wheel, in particular the McLaren GT3 at the top.

Beyond the silhouette, I had to also work on choices for inputs, which is the most customisable aspect of this build, with such variety available to use, I opted to go for options that were the simplest, removing any additional margin for error, at least for this first wheel. As a result i chose a simple momentary push button to use primarily for the 2 pins, with little adjustment needed in terms of voltage or current due to the simple structure of the button.

<img src="/assets/images/pushbutton.png">


### A fairly easy, universal button choice, any variation of a button could have sufficed.

Shifters were a more difficult problem, as the initial plan was to use spring loaded shifters, however, it became increasingly obvious that magnetics were a better choice, not only because they were better feeling, but they were also far easier to implement. The most crucial component for the switches for the shifters, and I eventually landed on the Omron SS-5, a compact switch which fulfilled all my needs, with a small current draw allowing it to connect directly to the pro micro without additional components.

<div style="display: flex; gap: 15px; justify-content: center; align-items: center; flex-wrap: wrap; margin-bottom: 15px;">
  <img src="/assets/images/omron.jpg" width="48%">
  <img src="/assets/images/shifter.png" width="48%">
</div>

### Switch and shifter, they felt good and were compact enough to implement into the rest of the wheel.

## Design

To start, I first made a rough outline for the baseplate of the wheel, ensuring that it is a properly scaled wheel and fits my dimension of 280-300mm long and about 150mm tall, before adding a rough shape to represent the grips

<div style="display: flex; gap: 15px; justify-content: center; align-items: center; flex-wrap: wrap; margin-bottom: 15px;">
  <img src="/assets/images/baseplate1.png" width="48%">
  <img src="/assets/images/v1_1.png" width="48%">
</div>

### The baseplate was kept as 4mm thick, ensuring the aluminium was more than strong enough to at least support the 5Nm from a Moza R5

next on the agenda was creating shell to make a case -I'll call the backplate- where all of the electronics will be contained, and to do so i just traced an outline around where the grips would stop on the backplate and created a new body that i hollowed out. on top of this, i remoulded the grips, getting a feel for how a person would grab them and editing them to fit that shape more ergonomically, as well as adding screw holes to attach the grips to the baseplate.

<img src="/assets/images/v1_2.png">

## The First print

The next step I wanted to take was make a print of of what I had built so far, to ensure that what I was making was accurate, and felt good to use and interact with, as well as allowing me to physically take measurements and put different things into perspective. I used my University's makerspace alot for this, utilising their array of Bambu 3D printers.

<div style="display: flex; gap: 15px; justify-content: center; align-items: center; flex-wrap: wrap;">
  <img src="/assets/images/print1_1.jpg" width="48%">
  <img src="/assets/images/print1_2.jpg" width="48%">
</div>

I figured out a few things from this, button placements and where my hand would feel most comfortable placing them, as well as how to edit the grips to provide a slightly improved feel to them.

This then led me to start working on the backplate more, and planning out the layout for the buttons, electronics, screw holes and the quick release, which was my immediate concern, as it led to one of the designs I wanted to use for the shifters being ruled out due to being too bulky without immense modifications, which led me to finding a new design for them, as well as where specifically to place the quick release.

<div style="display: flex; gap: 15px; justify-content: center; align-items: center; flex-wrap: wrap; margin-bottom: 15px;">
  <img src="/assets/images/v1.3_1.png" width="48%">
  <img src="/assets/images/v1.3_2.png" width="48%">
</div>

Next, I planned out the button layout with the buttons I had, as well as adding screw holes, based on where i felt they would best work looking at the first prints i made for the wheel, as well as creating an initial design for where the quick release would attach to.

<div style="display: flex; gap: 15px; justify-content: center; align-items: center; flex-wrap: wrap; margin-bottom: 15px;">
  <img src="/assets/images/v1.32_1.png" width="48%">
  <img src="/assets/images/v1.32_2.png" width="48%">
</div>

### In retrospect, the amount of screws were quite excessive and made for lengthy disassembly and reassembly, as well as creating a fatal flaw I will address later.

For the final touches, I edited the backplate mount, as I realised how much longer it would take to print (almost 6 hours total!) as well as giving practically no benefit overall, so ended up making it flat to match up with the rest of the backplate.

<img src="/assets/images/v1.33.png">

This plus some final edits to the layouts for the buttons i realised after checking an updated frontplate with screw mounts led to the final model for the wheel!

<img src="/assets/images/v1.34.png">

## Assembly and electronics

At this point I moved onto fully building the wheel, buying the materials needed such as the quick release adapter, aluminium, magnets and switches.

First on the agenda was getting the baseplate cut from aluminium and testing the buttons and grips fit properly, which thankfully all fit together properly, then it was printing the chassis for the shifters as well as the backplate to see how they all fit together in case any final adjustments were needed.

<div style="display: flex; gap: 15px; justify-content: center; align-items: center; flex-wrap: wrap; margin-bottom: 15px;">
  <img src="/assets/images/IMG20260727181056.jpg" width="48%" style="transform: rotate(-90deg);">
  <img src="/assets/images/IMG20260727181102.jpg" width="48%" style="transform: rotate(-90deg);">
</div>

### The printing seemed to go well, though the colours ended up clashing as i was using a variety of printers with varying filaments to get it done quicker.

At this point, the first flaw in my design showed up - there was no proper hole for a cable to go out of the wheel and connect to the wheel, which was remedied with drilling a hole into the wheel at the cost of alot of structural integrity.

<div style="display: flex; gap: 15px; justify-content: center; align-items: center; flex-wrap: wrap; margin-bottom: 15px;">
  <img src="/assets/images/IMG20260727183346.jpg" width="50%">
  <img src="/assets/images/IMG20260727183351.jpg" width="50%">
</div>

### They fit together seamlessly which was a great relief for me!

Next on the agenda was beginning work on the wiring and soldering. For this project I was using an Arduino Pro Micro, due to the vast amounts of documentation covering similar projects utilising it, making it very easy to use as any issues were more easy to diagnose quickly, as well as having compatibility with simhub which makes the wheel being recognised as a proper wheel much easier.

<img src="/assets/images/arduino.png">

To begin with, I started working on soldering the shifter modules first, due the very finicky nature of them, I felt getting the most difficult part out of the way immediately was the best course of action. However, in hindsight, connecting wires to the button modules first then the Arduino after caused major headaches for trying to cable manage and effectively keep the Arduino in place at all, but more on that later.

<img src="/assets/images/IMG20260810144441.jpg">

Finally, I had to begin soldering the rest of the components to the Arduino. I quickly realised I didn't have any way to properly connect all of the grounds, so as a makeshift solution i cut off a piece of perfboard to act as a common ground for all inputs to connect to the Arduino. This, plus the error of soldering my components first let to the cable monstrosity i ended up producing as a result of all of this-

<img src="/assets/images/IMG20260812122715.jpg">

Another detail- i realised i needed to tape this to something, and it would not stick to the PLA at all, so I had to settle for layering electrical tape on the aluminium and taping it to that instead. But, the only part that really mattered to me was that it worked!

<img src="/assets/images/IMG20260813112149.jpg">

### It lives!

Finally, I could start working on the software side of the project, which was made very simple by Simhub, which paired with some C++, let me setup the wheel and make sure it was fully working within an hour

<div style="display: flex; gap: 15px; justify-content: center; align-items: center; flex-wrap: wrap; margin-bottom: 15px;">
  <img src="/assets/images/simhub.png" width="48%">
  <img src="/assets/images/c++code.png" width="48%">
</div>
