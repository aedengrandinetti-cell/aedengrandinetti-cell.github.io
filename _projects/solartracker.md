---
layout: page
title: Solar Tracker
description: Arduino-powered solar tracking device built at the University of Arizona
img: assets/img/solar_tracker.jpg
importance: 2
category: work
---

While I was studying at the University of Arizona, another project that I built for an engineering class was a solar tracker device. The purpose of the device was to use photoresistors attached to an Arduino controlling a servo motor to follow the sun, in order to align an attached solar panel with the sunlight to store energy and power itself.

<div class="row">
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/solar_tracker.jpg" title="Assembling the solar tracker" class="img-fluid rounded z-depth-1" %}
  </div>
</div>

This is me putting it together, using masking tape in the areas where the Thingiverse print failed. At this point in my engineering experience I did not know how to use CAD, and as such I reassembled an existing layout. This experience taught me a lot about interfacing with the work of previous engineers, as well as learning to fix small bugs in the reassembly process. For example, the CAD file that I pulled from online actually was made to have 4 photoresistors, however our kit only gave us two, and so I had to alter certain things about the structure of the printed scaffold in order to give myself the results that I wanted, with the limited tools that I had.

After designing and implementing the code, and the structure of the solar tracker, it was time to display them in class.

<div class="row">
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/testing_solar_tracker.png" title="Testing the solar tracker" class="img-fluid rounded z-depth-1" %}
  </div>
</div>

Due to the time constraints of the project, I ran into a stubborn bug in my code — the tracker ended up chasing darkness instead of light, exactly the opposite of the intended behavior! Thankfully, my teacher decided to give me an A, and later that year I took and aced a C# coding class and was able to fix my solar tracker code, since the Arduino language and C are so similar! It was a really fun learning process and also a challenging exercise in problem solving that allowed me to grow a fondness for microcontroller engineering projects.
