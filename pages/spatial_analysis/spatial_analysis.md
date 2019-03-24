---
layout: process
title: M.A.G //004
category: M.A.G
subcategory: 
description: Spatial Analysis & Simulation // ML & Sensors
dependencies: [ 'Lines' ]
platforms: [ 'Rhinoceros','Grasshopper' ]
heroimg: ITL-01.jpg
order: 4
thumb: thumb.png
---

<hr class="homebreak">

## Spatial Analysis & Simulation // ML & Sensors
---

Since the creation of Arduino back in 2003, low cost microcontrollers powered IoT devices collecting Big Data has become ubiquitous in our society. Although the applications of these data is very wide, from weather monitoring, surveillance and security, to the commercialization of our privacy, the art and design world have yet to interrogate the potentials of this technology, to the extent where it can fundamentally challenge our thinking and design paradigm. 

Our research in this area was initiated by a series of conversations with our potential collaborators and by the internal needs within the institute. It started simply as a way to ask simple question with regard to the nature of space. Is the room too big or too small? Is the layout efficient? Are the furniture enhancing or disrupting people's concentration? As architects, understanding how space affects our behavior is one of the fundamental foundations in our profession. However, the ability to see beyond the temporal dimension is only possessed by very few, such as Jane Jacobs' assertion that eyes on the street make a safe and intimate neighborhood. However, strong observation is only the beginning of the scientific method, and we need much more than doctrines in the age of big data to inform high level decisions that may impact many.... blurb



<iframe width="100%" height="600" src="https://www.youtube.com/embed/ZnPfhx3L0Lg?rel=0;&autoplay=1&mute=1" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<iframe width="100%" height="600" src="https://www.youtube.com/embed/ZghiIqtgPDk?rel=0;&autoplay=0&mute=1" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>



<div class="sketchfab-embed-wrapper"><iframe width="100%" height="400" src="https://sketchfab.com/models/cf230a87371c4df18d9ab2301bd7e731/embed" frameborder="0" allow="autoplay; fullscreen; vr" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>


<p style="font-size: 13px; font-weight: normal; margin: 5px; color: #4A4A4A;">
    <a href="https://sketchfab.com/3d-models/itl-office-cf230a87371c4df18d9ab2301bd7e731?utm_medium=embed&utm_source=website&utm_campaign=share-popup" target="_blank" style="font-weight: bold; color: #1CAAD9;">ITL Office</a>
    by <a href="https://sketchfab.com/itl?utm_medium=embed&utm_source=website&utm_campaign=share-popup" target="_blank" style="font-weight: bold; color: #1CAAD9;">itl</a>
    on <a href="https://sketchfab.com?utm_medium=embed&utm_source=website&utm_campaign=share-popup" target="_blank" style="font-weight: bold; color: #1CAAD9;">Sketchfab</a>
</p>
</div>





<div class="sketchfab-embed-wrapper"><iframe width="100%" height="400" src="https://sketchfab.com/models/f4564279025c427f9112eff864cf9e2c/embed" frameborder="0" allow="autoplay; fullscreen; vr" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>


<p style="font-size: 13px; font-weight: normal; margin: 5px; color: #4A4A4A;">
    <a href="https://sketchfab.com/3d-models/itl-18th-st-f4564279025c427f9112eff864cf9e2c?utm_medium=embed&utm_source=website&utm_campaign=share-popup" target="_blank" style="font-weight: bold; color: #1CAAD9;">ITL 18th St</a>
    by <a href="https://sketchfab.com/itl?utm_medium=embed&utm_source=website&utm_campaign=share-popup" target="_blank" style="font-weight: bold; color: #1CAAD9;">itl</a>
    on <a href="https://sketchfab.com?utm_medium=embed&utm_source=website&utm_campaign=share-popup" target="_blank" style="font-weight: bold; color: #1CAAD9;">Sketchfab</a>
</p>
</div>

#### Walkthrough

- **Reference** your **surface** in **grasshopper** with a surface parameter object.

- Drop in a Quad Panels component from the **Lunchbox** toolbar

- Add integer sliders for the U and V divisions of the surface, and plug them into their respective inputs. These will dictate how many panels the component should create in the U and V axis of the surface

- You can divide into panels of an **approximate size** by using the **Dimensions** component and dividing by the desired panel size in that direction, then feeding the result into its respective input on the component

  

---
