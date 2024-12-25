---
layout: page
title: CameraMouse & KeyGlide
description: AI-based technologies for accessible device control.
importance: 1
img: assets/img/cameramouse/CM 1.png
category: work
giscus_comments: false
---

We developed CameraMouseAI and KeyGlide to enhance accessibility and device control for people with severe motor impairments, like MS ans ALS.
CameraMouseAI is a system that enables mouse control using head movements, tracking the tip of the user's nose. Users perform clicks, by raising their eyebrows or opening their mouth, in addition to traditional dwell-time selection. The app's strength is in its extensive customization - the user can change the sensitivity of the mouse, exclude areas of the screen and alter thresholds for the facial gestures.
The open-source platform allows for easy updates and extensions with new computer vision and machine learning models. In tests, both users with and without motor impairments successfully used CameraMouseAI for tasks like target selection and web browsing.

To enable textual input with minimal precision, KeyGlide lets the user select letters using simple side-to-side movement of the mouse, using CameraMouseAI or any other accessible mouse. The user picks the letter group, then the letter by moving into the specified area at the right time. Typing is further enhanced using word prediction, completion and spell-check. Users with motor impairments tested KeyGlide and were able to input phrases of 3-5 accurately (String Distance values of 3-4).

### CameraMouseAI

<div class="row">
    <div class="col-sm mt-6 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/cameramouse/CM 1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-6 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/cameramouse/CM 2.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

### KeyGlide

{% include figure.liquid loading="eager" path="assets/img/cameramouse/KeyGlide.png" title="Layout of kEYgLIDE" class="img-fluid rounded z-depth-1" %}

<div class="caption">
    Layout of KeyGlide. The orange bed sequentially highlights the letter groups. The user moves from the rest area (right) to the key area (left), at the appropriate time to select the letter group. Similarly for the letter. 
</div>
