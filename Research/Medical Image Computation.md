---
layout: page
title: Medical Image Computation
permalink: /Research/Medical Image Computation/
---

Medical image computation is my main theme as a master student at Shanghai Jiao Tong University last year. Around it, I acquired skills of image visualization (VTK), medical image processing (ITK) and delved into Deep Learning. I also improved my coding skills using C++ and QT.

&nbsp;

{% include image.html url="/images/registration.gif" caption="demo" width=345 align="right" %}

### **[[Code](https://github.com/dzzhang96/Points-Registration-ICP)] Orbital Rim Registration Software V1.0**

01/2020-06/2020

*Master Projects, Supervisor: Dr. Xiaojun Chen*

- A software for point clouds registration based on VTK7.0 and Qt5.0. (you can cmake it😀)The basic algorithm is ICP, the number of iterations is set to 50.

- The upper left window renders the stable STL while the upper right window can be input several STLs for transformation.

- You can either registrate by right clicking (to get points) on STL or registrate directly by point clouds.

You can find the code [here](https://github.com/dzzhang96/Points-Registration-ICP).

### **[[Code](https://github.com/dzzhang96/tf-predict-cpp)] Medical Image Segmentation using Tensorflow C++ API**

09/2019-11/2019

{% include image.html url="/images/tensor.jpg" caption="segment the bone craft in maxillary sinus" width=365 align="right" %}

*Master Projects, Supervisor: Dr. Xiaojun Chen*

- Shortened calculation time for medical image computation software by integrating deep learning.

- Compiled the Tensorflow C++ library and converted Python image segmentation programs to C++.

- Developed semi-automatic labeling algorithms to segment a bone graft using maxillary sinus for training models.

You can find the code [here](https://github.com/dzzhang96/tf-predict-cpp).
