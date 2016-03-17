---
title:  "Orrery - Final Presentation"
date:   2016-03-16 23:34:23
categories: [milestones]
tags: [milestones]
---

Here is our last milestone for our orrery project, we will describe what we implemented illustrated with a small video of our project in use.

{% include youtube.html id='SKNPG8h8ycM' %}

Since the next post, we have implemented the 5 required interactions tasks :

- selection
- manipulation
- wayfinding
- travel
- system control

The selection part is done with a simple raycasting, starting from the end of the stylus to a maximum bound where our interface is implemented.

The manipulation part is now activated when you have selected a planet and the button is pressed more than one second, when the manipulation state is entered, the planet will try to follow the stylus but the planet will stay on its orbit.

The wayfinding part is done with a miniworld, in fact, a mini solar system that permit to totally understand where the planet is and how the others neighbourhood planet rotate.

The travel part has been implemented with two different buttons, the first one is used to zoom on a specific planet system, the second one is used to unzoom into the parent planet system.

We also have implemented two different button that help us to increase or decrease the time. When you will increase the time, the planet will rotate more speedly than before and at the opposite, when you will decrease the time the planet will move slowly. We can also decrease the time in order to go back in the time curvature, the planet will then go in the opposite direction.


Finally, The planet's orbit are calculated using the the six Keplerian orbital elements. We also take into account the planet's axial tilt for it's rotation.
