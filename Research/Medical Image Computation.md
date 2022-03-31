---
layout: page
title: Medical Image Computation
permalink: /Research/Medical Image Computation/
---

I gained most of my experience in medical image processing at Shanghai Jiaotong University as a graduate student from year 2019. I acquired skills of **OpenCV**, image visualization (**VTK**), medical image processing (**ITK**), software development (**Qt**) and then delved into **Deep Learning**. Concurrently, I progressed my coding skills using **C++** and **Python**.

## Publications
### Revising:
Jiangchang Xu, **Dingzhong Zhang**, Chunliang Wang, Huifang Zhou, Yinwei Li, and Xiaojun Chen*. (2021). Automatic Segmentation of Orbital Wall from CT Images Using a Fully Convolutional Network Based on Thin Wall Region Supervision. Medical Physics.

### Reviewing:
Yuwei Gu, **Dingzhong Zhang**, Baoxin Tao, Feng Wang, Xiaojun Chen*, Yiqun Wu*. (2021). A novel technique to quantify radiographic bone-to-implant contact of zygomatic implants based on three-dimensional image registration and segmentation. Dentomaxillofacial Radiology.

### Published:
Haitao Li<sup>#</sup>, Jiangchang Xu<sup>#</sup>, **Dingzhong Zhang**, Yaohua He, Xiaojun Chen*. (2022). An Automatic Surgical Planning Combining Bone Density Assessment and Path Integral in Cone Area for Reverse Shoulder Arthroplasty. International Journal of Computer Assisted Radiology and Surgery.

Jiangchang Xu<sup>#</sup>, Jiannan Liu<sup>#</sup>, **Dingzhong Zhang**, Zijie Zhou, Chenping Zhang, Xiaojun Chen*. (2021). A 3D Segmentation Network of Mandible from CT Scan with Combination of Multiple Convolutional Modules and Edge Supervision in Mandibular Reconstruction. Computers in Biology and Medicine.

Jiangchang Xu<sup>#</sup>, Jiannan Liu<sup>#</sup>, **Dingzhong Zhang**, Zijie Zhou, Xiaoyi Jiang, Chenping Zhang, Xiaojun Chen*. (2021). Automatic Mandible Segmentation from CT Image Using 3D Fully Convolutional Neural Network Based on DenseASPP and Attention Gates. International Journal of Computer Assisted Radiology and Surgery.

Afaque Memon, Dongyuan Li, Junlei Hu, Enpeng Wang, **Dingzhong Zhang**, Xiaojun Chen*. (2021). The Development of Computer‐aided Patient‐Specific Template Design Software for 3D printing in Cranio‐Maxillofacial Surgery. The International Journal of Medical Robotics and Computer Assisted Surgery.

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

### **[[Code](https://github.com/dzzhang96/tf-predict-cpp)] Medical Image Segmentation using Tensorflow C++ API**

09/2019-11/2019

{% include image.html url="/images/vnet.jpg" caption="Mandible Segmentation" width=365 align="right" %}

*Master Project, Supervisor: Dr. Xiaojun Chen*

- Shortened calculation time for medical image computation software by integrating deep learning.

- Compiled the Tensorflow C++ library and converted image segmentation programs from Python to C++.

- Developed automatic labeling algorithms based on U-net/V-net to segment mandible and bone graft in maxillary sinus.

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
