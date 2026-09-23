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





