---
layout: page
title: Nuclear graphite bricks
description: Work for EDF Energy
img: assets/img/main_projects/edf_brick1.png
importance: 3
category: main
---



Brittle fracture in nuclear graphite
In this project, I was working on fracture in Nuclear-Graphite supported by EDF Energy. The research focused on establishing 3d crack propagation theory, numerical methods, and robust implementation.


Although my PhD research was focused on bone fatigue fracture prevention, it has turned into contribution to assessing the structural integrity of nuclear power plants in the UK. I paused my PhD for three months to support project on modelling of fracture in irradiated graphite bricks in Advanced Gas-Cooled Reactors in collaboration with industrial partners (EDF Energy and Jacobs). I was responsible for extending the functionality of MoFEM to efficiently map the heterogeneous fields and improve the postprocessing, to enhance the code’s HPC capabilities. Furthermore, I gained experience in interaction with the industry through numerous technical sessions and progress meetings. I contributed to organisation of the two workshops at UofG in 2020 aimed at advising our partners in performing simulations using our code. Thanks to sustainable development practices adopted in the MoFEM team, our industrial partners were able to use novel technology to perform simulations required to support safety cases for the UK nuclear power plants’ operations. This work led to the submission of an impact case to REF2021 (The Research Excellence Framework). 

****

Every project has a beautiful feature showcase page.
It's easy to include images in a flexible 3-column grid format.
Make your photos 1/3, 2/3, or full width.


[![Watch the video](https://img.youtube.com/vi/581MZC-hW0k/0.jpg)](https://youtu.be/581MZC-hW0k)

[<img src="https://img.youtube.com/vi/581MZC-hW0k/maxresdefault.jpg" width="50%">](https://youtu.be/581MZC-hW0k)

To give your project a background in the portfolio page, just add the img tag to the front matter like so:

    ---
    layout: page
    title: project
    description: a project with a background image
    img: /assets/img/12.jpg
    ---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Caption photos easily. On the left, a road goes through a tunnel. Middle, leaves artistically fall in a hipster photoshoot. Right, in another hipster photoshoot, a lumberjack grasps a handful of pine needles.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div>

You can also put regular text between your rows of images.
Say you wanted to write a little bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, *bled* for your project, and then... you reveal it's glory in the next row of images.


<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
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
        {% include figure.html path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
```
{% endraw %}