---
layout: page
title: AR-based Surgical Navigation
permalink: /Research/AR-based Surgical Navigation/
---

{% include image.html url="/images/hololens.jpg" caption="Framework of AR based Surgical Navigation System" width=650 align="center" %}

### **Spine Surgical Navigation System based on AR using HoloLens**

09/2020-present

*McGill University: Master Thesis Project, Supervisor: Dr. Mark Driscoll, Co-supervisor: Dr. Jorge Angeles*

Developed an AR based surgical navigation system for high-quality visualization during spine surgery. Optimized the 3D reconstructed data from DICOM by using deep learning for automatic image segmentation.

**Part A:**
This part includes the surgical routes planning and unifying the coordinate systems of CT data, virtual/real models.

**Part B:**
An interfaced software includes the function of calibration of Polaris NDI and shows the real-time surgical routes on CT images. The probe and passive 4-marker rigid body on the spine are used for Polaris NDI to track the position and orientation of the spine and surgical tools. 

**Part C:**
Accurate segmentation of the spine determines the quality of 3D reconstruction.

**Part D:**
An UWP is deployed into HoloLens which receives only real-time data and does not get involved in the computation.