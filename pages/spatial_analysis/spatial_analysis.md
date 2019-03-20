---
layout: process
title: SPATIAL ANALYTICS
category: M.A.G //001
subcategory: 
description: Sentient Collaborative Robotics // Scanning & Glazing
dependencies: [ 'Lines' ]
platforms: [ 'Rhinoceros','Grasshopper' ]
heroimg: ITL-01.jpg
order: 0
thumb: thumb.png
---

---
# Sensor Network Design Research
---


### Project Description

For the last 5 - 10 years, the development of IoT devices and the collection of Big Data for spatial intelligence, has been a dream come true for architects and designers. Since the days of of Frankfurt Kitchen and 



<div class="sketchfab-embed-wrapper"><iframe width="100%" height="400" src="https://sketchfab.com/models/cf230a87371c4df18d9ab2301bd7e731/embed" frameborder="0" allow="autoplay; fullscreen; vr" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>


<p style="font-size: 13px; font-weight: normal; margin: 5px; color: #4A4A4A;">
    <a href="https://sketchfab.com/3d-models/itl-office-cf230a87371c4df18d9ab2301bd7e731?utm_medium=embed&utm_source=website&utm_campaign=share-popup" target="_blank" style="font-weight: bold; color: #1CAAD9;">ITL Office</a>
    by <a href="https://sketchfab.com/itl?utm_medium=embed&utm_source=website&utm_campaign=share-popup" target="_blank" style="font-weight: bold; color: #1CAAD9;">itl</a>
    on <a href="https://sketchfab.com?utm_medium=embed&utm_source=website&utm_campaign=share-popup" target="_blank" style="font-weight: bold; color: #1CAAD9;">Sketchfab</a>
</p>
</div>



#### Walkthrough

- **Reference** your **surface** in **grasshopper** with a surface parameter object.

- Drop in a Quad Panels component from the **Lunchbox** toolbar

- Add integer sliders for the U and V divisions of the surface, and plug them into their respective inputs. These will dictate how many panels the component should create in the U and V axis of the surface

- You can divide into panels of an **approximate size** by using the **Dimensions** component and dividing by the desired panel size in that direction, then feeding the result into its respective input on the component

  ![](.\images\LunchboxPanels.gif)

---
