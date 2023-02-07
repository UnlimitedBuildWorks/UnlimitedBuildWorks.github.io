---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults
title: List of my portfolios
layout: page
---
# 1. [Research on Recording and Reproduction of Acoustic Realism (Master's Thesis in Japanese)](/assets/master_thesis.pdf)

This is a master's thesis that summarizes my research on the application of spatial(3D) sound to virtual reality, which I conducted during my time in the Hirose Laboratory at the University of Tokyo.

**I wrote my master's thesis in Japanese in 1994, and I am currently working on translating it into English.**

![Conceptual diagram of acoustic presence recording and playback system](/assets/pic1-1.png)
*Conceptual diagram of acoustic presence recording and playback system*
<br/>

***
<br/>

# 2. Demonstration of 'mocopi' device as angular (IMU) sensor w/o Sony's SDK.

<iframe width="638" height="1135" src="https://www.youtube.com/embed/eDkVJdibLJ0" title="mocopi IMU demo" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

***
<br/>

# 3. [Pseudo-3D display using a hemispherical display (in Japanese)](https://engineering.mercari.com/blog/entry/2018-12-11-120000/)

This article summarizes how to develop a pseudo-3D display Unity program using the hemispherical display type WORLDEYE from Gakken and a depth sensor (RealSense D435).

![](/assets/pic2-1.jpg)
*Overall configuration of the pseudo-3D display system*

<iframe width="560" height="315" src="https://www.youtube.com/embed/h90oY6eslwk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<br/>

***
<br/>

# 4. Making Oculus Go 6DoF with RealSense T265

Although RealSense products are incompatible with Android, I made a 6DoF version of Oculus Go HMD using V-SLAM device (RealSense T265) by modifying the Intel Realsense SDK.

Click [here](https://www.slideshare.net/mitsunorisatomi5/androidrealsense-d400t265) for slides in Japanese.

![6DoF Oculus Go](/assets/pic3-1.jpg)
*6DoF Oculus Go*

<iframe width="560" height="315" src="https://www.youtube.com/embed/TJmLAkr6YX8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<br/>

***
<br/>

# 5. Classical Ray-Tracing renderer porting to C# code running on Unity Engine

I ported the ray-tracing rendering engine I developed in the 1980s to the C# language and tried to draw computer graphics on the Unity engine.

At the time, the program implemented the following cutting-edge technologies.

* An accelerated ray tracing technique using a binary tree-based spatial decomposition method.
* Curved Surface Modeling Technology Using Metaball Technology.
* Development of Floating-Point Optimized Compilation Technology for Motorola 68020 MPU.

[Here](https://github.com/UnlimitedBuildWorks/EXRAYtracer) is the Github repository.

![Example of a robot model rendered by ray tracing.](/assets/pic4-1.png)  
*Example of a robot model rendered by ray tracing.*

![](/assets/pic4-2.png)  
*Example of a metaballs rendered by ray tracing.*

<br/>

***
<br/>

# 6. Ray tracing rendering system that supports Looking Glass.

I developed a Unity program so that images drawn by the ray tracing engine ported in the fourth section can be viewed on the Looking Glass three-dimensional display.

<iframe width="560" height="315" src="https://www.youtube.com/embed/vdh2d5QDAt0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<br/>

***
<br/>

# 7. Looking Glass Free Viewpoint Viewer

At AWE USA 2019, I exhibited a viewer that allows users to lift the Looking Glass to view 3D objects from any perspective.

This Viewer program displays the image drawn in real time by Unity program on Looking Glass based on the position of Looking Glass 3D display device measured by V-SLAM device (RealSense T265).

<iframe width="560" height="315" src="https://www.youtube.com/embed/kj9qpgcOim8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
