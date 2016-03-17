---
title:  "Orrery - Final Presentation"
date:   2016-03-16 23:34:23
categories: [milestones]
tags: [milestones]
---

Hi,

Here is our video for our orrery project :

{% include youtube.html id='mGE7bhz5uRQ' %}

Since the next post, we have implemented the 5 required interactions tasks :

- selection
- manipulation
- wayfinding
- travel
- system control

We can select a planet with a raycasted ray, using the ZSpace stylus.

When the planet is selected, we can move the planet in its orbit by just staying pressed on the stylus button. The planet position will be set to the new position that we obtain with the intersection of the stylus on the plane.

In order to always now were we are in the Solar System, we have a mini-world in movement in the front right side, this mini-world show only the parent system.

We can travel between the differents planet, what we have implemented is pretty simple :

    1. select the planet
    2. Click the zoom button

In order to go back to the parent planet, we just need to click on the unzoom button.

