---
author: Leandro
comments: true
date: 2013-12-06 13:37:37+00:00
layout: post
slug: vertex-discard-occlusion-culling
title: Vertex Discard Occlusion Culling
wordpress_id: 118
categories:
- Published
- Research
---

### Paper

Published in SeDICI: [Vertex discard occlusion culling](http://sedici.unlp.edu.ar/handle/10915/31657)

### Abstract
>
Performing visibility determination in densely occluded environments is essential to avoid rendering unnecessary objects and achieve high frame rates. In this work we present an implementation of the image space Occlusion Culling algorithm done completely in GPU, avoiding the latency introduced by returning the visibility results to the CPU. Our algorithm utilizes the GPU rendering power to construct the Occlusion Map and then performs the image space visibility test by splitting the region of the screen space occludees into parallelizable blocks. Our implementation is especially applicable for lowend graphics hardware and the visibility results are accessible by GPU shaders. It can be applied with excellent results in scenes where pixel shaders alter the depth values of the pixels, without interfering with hardware Early-Z culling methods. We demonstrate the benefits and show the results of this method in real-time densely occluded scenes.
>

### Authors
>
Barbagallo, Leandro R., Leone, Matias N., García, Rodrigo N.


### Presented
>
XI Workshop on Computer Graphics, Images and Visualization (WCGIV)
Argentine Congress on Computer Sciences (CACIC) - October 21 to October 25 - 2013 - Mar del Plata - Argentina
[CACIC 2013](http://cacic2013.ucaecemdp.edu.ar/)

### Contact

lbarbagallo@frba.utn.edu.ar
