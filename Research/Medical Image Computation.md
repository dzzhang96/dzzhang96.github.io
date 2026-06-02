---
layout: page
title: Medical Image Computation
permalink: /Research/Medical Image Computation/
---

I gained extensive experience in **medical image processing** during my graduate studies at **Shanghai Jiao Tong University**, beginning in 2019. Throughout this period, I developed strong expertise in **OpenCV**, medical image processing with **ITK**, visualization using **VTK**, and software development with **Qt**. Building upon these foundations, I further expanded my skill set into **Deep Learning** for medical image analysis. Concurrently, I strengthened my programming proficiency in both **C++** and **Python**, which have become my primary development languages.

&nbsp;

## Projects
{% include image.html url="/images/registration.gif" caption="Orbital Rim Registration Software V1.0" width=345 align="right" %}

### **[[Code](https://github.com/dzzhang96/Points-Registration-ICP)] Orbital Rim Registration Software V1.1**

01/2020-06/2020

*Master Project, Supervisor: Dr. Xiaojun Chen*

- A software for point clouds registration based on VTK7.0 and Qt5.0. (you can cmake it😀)The basic algorithm is ICP, the number of iterations is set to 50.

- The upper left window renders the stable STL while the upper right window can be input several STLs for transformation.

- You can either registrate by right clicking (to get points) on STL or registrate directly by point clouds.

You can find details [here](https://github.com/dzzhang96/Points-Registration-ICP).

### **[[Code](https://github.com/dzzhang96/tf-predict-cpp)] Bone Graft Segmentation in Maxillary Sinus using Tensorflow C++ API**

09/2019-11/2019

{% include image.html url="/images/vnet.jpg" caption="Mandible Segmentation" width=365 align="right" %}

*Master Project, Supervisor: Dr. Xiaojun Chen*

- Reduced computation time of a medical image computation software by 80% through integration of DL models.
- Compiled the TensorFlow C++ library and translated the segmentation pipelines from Python to C++ for deployment and performance optimization.
- Developed semi-automatic labelling algorithms to segment the bone graft from maxillary sinus for training.

You can find the code [here](https://github.com/dzzhang96/tf-predict-cpp).

### **[[Code](https://github.com/dzzhang96/Medical-Image-Processing)] Course Project of Advanced Biomedical Image Processing**

04/2020-06/2020

{% include image.html url="/images/ezgif-4-f6c54188bf18.gif" caption="A QT GUI" width=365 align="right" %}

*Course Project, Advanced Biomedical Image Processing*

Implemented several traditional algorithms in C++ with OpenCV3.4, VTK7.0 and QtGui.

- Thresholding: OTSU & Entropy and Histgram

- Convolution: Roberts & Sobel & Prewitt Operator and Gaussian & Median Filter

- Morphology: Basic Operations, Morphological Edge Detection, Gray Scale Reconstruction, Distance Transform & Skeleton and Conditional Dilation

You can find the code [here](https://github.com/dzzhang96/Medical-Image-Processing).
