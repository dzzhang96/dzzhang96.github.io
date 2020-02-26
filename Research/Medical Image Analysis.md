---
layout: page
title: Medical Image Analysis
permalink: /Research/Medical Image Analysis/
---

Medical image analysis is my main theme since I entered Shanghai Jiaotong University as a master student last year. Around it, I acquired skills of image visualization (VTK), medical image processing (ITK) and delved into Deep Learning. I also progressed my coding skills through programming practical softwares in C++ and QT.

&nbsp;

{% include image.html url="/images/registration.gif" caption="demo" width=345 align="right" %}

### **[[Code](https://github.com/dzzhang96/Points-Registration-ICP)] Orbital Rim Registration Software V1.0**

01/2020-present

*Master Projects, Supervisor: Dr. Xiaojun Chen*

- A software for point clouds registration based on VTK7.0 and Qt5.0. (you can cmake it😀)The basic algorithm is ICP, the number of iterations is set to 50.

- The upper left window renders the stable STL while the upper right window can be input several STLs for transformation.

- You can either registrate by right clicking (to get points) on STL or registrate directly by point clouds.

You can find the code [here](https://github.com/dzzhang96/Points-Registration-ICP).

### **[[Code](https://github.com/dzzhang96/tf-predict-cpp)] Medical Image Segmentation using Tensorflow C++ API**

09/2019-11/2019

{% include image.html url="/images/tensor.jpg" caption="segment the bone craft in maxillary sinus" width=365 align="right" %}

*Master Projects, Supervisor: Dr. Xiaojun Chen*

- Manually segmented the bone graft in maxillary sinus to get the mask for training models based on U-net 2D and 3D.

- Compiled Tensorflow C++ library and converted Python image segmentation programs to C++ code for prediction

- Defined a class to integrate deep learning into other medical image processing software.

You can find the code [here](https://github.com/dzzhang96/tf-predict-cpp).
