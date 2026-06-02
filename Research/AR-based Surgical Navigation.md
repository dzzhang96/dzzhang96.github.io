---
layout: page
title: AR-based Surgical Navigation
permalink: /Research/AR-based Surgical Navigation/
---


### **Key Techniques of an AR-based Spine Surgical Navigation System**

10/2020-02/2022

*McGill University: Master Thesis Project, Supervisor: [Dr. Mark Driscoll](https://www.mcgill.ca/mecheng/people/staff/mark-driscoll), Co-supervisor: [Dr. Jorge Angeles](https://www.mcgill.ca/mecheng/people/staff/jorgeangeles), [Dr. Ahmed Aoude](https://www.mcgill.ca/orthopaedics/our-team/ahmed-aoude-md-frcsc)*

{% include image.html url="/images/faroarm.jpg" caption="Accuracy Assessment of CT-based Spine Bone
Reconstruction using *FaroArm*" width=850 align="center" %}

Proposed and implemented a coordinate measurement framework using the *FaroArm*, a high-precision articulated measurement arm, to evaluate the geometric accuracy of lumbar spine models reconstructed from CT images. Developed a **landmark-based registration algorithm** for system calibration and quantitatively assessed reconstruction errors of the virtual anatomical models.

{% include image.html url="/images/hololens.jpg" caption="Framework of AR based Spine Surgical Navigation System" width=850 align="center" %}

Developed an **AR-based surgical navigation system** for spine surgery to enhance intraoperative visualization and navigation accuracy. The system incorporated **calibration** between *HoloLens*, surgical instruments, and *Polaris NDI* (an optical surgical tracking system), as well as **registration** between physical anatomy and virtual 3D models for real-time surgical guidance.




**Part 1:**
This part is the registration procedure that aligns the coordinate system of the patient's anatomy with the preoperative CT-derived virtual spine model. Landmark registration can be used if corresponding fiducial markers are selected. Surface registration is another approach by sliding the probe on the surface of bone to collect a seires of points. Other image-guided registration methods include X-ray/DRR registration using C-arm and O-arm.

**Part 2:**
Developed calibration procedures for tracked surgical instruments to accurately determine the spatial relationship between the instrument tip and the tracking markers. For example, probe-to-drill calibration was performed by aligning the probe tip with the drill tip while maintaining axial alignment, enabling accurate tracking of the drill tip during navigation.

**Part 3:**
Automatic segmentation of vertebra using deep learning (variations of UNet) and 3D reconstruction from the segmentation mask.

**Part 4:**
The calibration of HoloLens. A custom 3D-printed calibration cube was designed to establish the transformation between the HoloLens coordinate system and the optical tracking system. A **dual-quaternion-based calibration algorithm** was implemented to enable efficient and accurate registration. A lightweight **UWP application** was deployed on the HoloLens to receive real-time tracking and navigation data, while all computationally intensive processing was performed externally to minimize device workload and latency.


***Screenshot of the navigation software under development:***
{% include image.html url="/images/software.jpg" caption="AR-based Surgical Navigation Software" width=850 align="center" %}

### **Automatic Surgical Routes Planning for Reverse Total Shoulder Arthroplasty**

12/2020-08/2021

*Shanghai Jiao Tong University: Master Project, Supervisor: Dr. Xiaojun Chen*
{% include image.html url="/images/rtsa.png" caption="RTSA Surgical Navigation Software" width=850 align="center" %}