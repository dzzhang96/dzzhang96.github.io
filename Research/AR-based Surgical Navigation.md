---
layout: page
title: AR-based Surgical Navigation
permalink: /Research/AR-based Surgical Navigation/
---


### **Key Techniques of An AR-based Spine Surgical Navigation System**

09/2020-present

*McGill University: Master Thesis Project, Supervisor: [Dr. Mark Driscoll](https://www.mcgill.ca/mecheng/people/staff/mark-driscoll), Co-supervisor: [Dr. Jorge Angeles](https://www.mcgill.ca/mecheng/people/staff/jorgeangeles), [Dr. Ahmed Aoude](https://www.mcgill.ca/orthopaedics/our-team/ahmed-aoude-md-frcsc)*

{% include image.html url="/images/faroarm.jpg" caption="Accuracy Assessment of CT-based Spine Bone
Reconstruction using *FaroArm*" width=650 align="center" %}

Proposed a coordinate-measurement solution using the *FaroArm*, a high-precision measuring robotic arm, to evaluate the accuracy of the virtual lumbar spine model reconstructed from CT images. A **landmark registration algorithm** was used for calibration. The error from the reconstruction procedures for the virtual model were quantified.

{% include image.html url="/images/hololens.jpg" caption="Framework of AR based Surgical Navigation System" width=650 align="center" %}

Developed an AR based surgical navigation system for high-quality visualization and accurate navigation during the spine surgery. This includes the **calibration** of *HoloLens* and *Polaris NDI* (a surgical tool tracking device), the **registration** between real and virtual models

**Part A:**
This part includes the surgical routes planning and unifying the coordinate systems of CT data, virtual/real models.

**Part B:**
An interfaced software includes the function of calibration of Polaris NDI and shows the real-time surgical routes on CT images. The probe and passive 4-marker rigid body on the spine are used for Polaris NDI to track the position and orientation of the spine and surgical tools. 

**Part C:**
Automatic segmentation of vertebra using deep learning (a variation of U-net) and then 3D reconstruction.

**Part D:**
An UWP is deployed into HoloLens which receives only real-time data and does not get involved in the computation.

**Screenshot of the navigation software under development**
{% include image.html url="/images/software.jpg" caption="AR based Surgical Navigation Software" width=650 align="center" %}