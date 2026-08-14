---
layout: page
title: ESSENCE CubeSat Mission
description: "From concept to orbit: Engineering a university student-led satellite mission."
img: assets/img/essence_logo_png.png
importance: 1
category: work
tags: [Systems Engineering, V&V, Space Engineering]
---

It is a rare privilege to be part of a satellite mission from its initial whiteboard concepts all the way to a successful orbital launch. It is even rarer when that entire lifecycle is driven by a team of university students. 

The ESSENCE CubeSat mission was exactly that: a fully student-led space project that demanded professional-grade engineering, rigorous testing, and uncompromising project management to design a working satellite and launch it into space within 2 years.

## The Mission & The Challenge
ESSENCE was a 3U CubeSat planned to be in orbital operations for 2 years. While in orbit, it took images of ice melt in northern communities using an earth observation payload designed by Canadensys. It additionally had a secondary payload in the form of an ADCS experiment which tested a hybrid ADCS strategy of using reaction wheels and magnetorquers. It also tested space worthiness of off the shelf components such as a Raspberry Pi Zero and an Arduino Uno by using them in some satellite subsystems.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/essence_mission_diag.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/essence_sat.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/essence_integration_test.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    On the left, the ESSENCE Mission Overview Diagram. Middle, the ESSENCE satellite poses for a photo at the Canadian Space Agency. Right, the final ESSENCE - NanoRacks Integration Test, AKA "the fit test".
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/essence_team_photo.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div>

You can also put regular text between your rows of images, even citations {% cite einstein1950meaning %}.
Say you wanted to write a bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, _bled_ for your project, and then... you reveal its glory in the next row of images.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    You can also have artistically styled 2/3 + 1/3 images, like these.
</div>

The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above:

{% raw %}

```html
<div class="row justify-content-sm-center">
  <div class="col-sm-8 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm-4 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
```

{% endraw %}
