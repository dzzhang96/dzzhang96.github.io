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

{% include image.html url="/images/hololens.jpg" caption="Framework of AR based Spine Surgical Navigation System" width=850 align="center" %}

Developed an AR-based surgical navigation system for high-quality visualization and accurate navigation during the spine surgery. This includes the **calibration** of *HoloLens* and surgical instruments using *Polaris NDI* (a surgical tool tracking device), the **registration** between real and virtual models

**Part 1:**
This part is the registration procedure linking the coordinate systems of virtual spine in CT image data with real patient. Landmark registration can be used if corresponding fiducial markers are selected. Surface registration is another approach by sliding the probe on the surface of bone to collect a seires of points. Others registration methods depend on X-ray/DRR registration using C-arm or O-arm.

**Part 2:**
The calibration of the surgical instruments. We use the tip of the probe to touch the tip of the drill and keep their axis aligned with each other.

**Part 3:**
Automatic segmentation of vertebra using deep learning (variations of U-net) and then 3D reconstruction.

**Part 4:**
The calibration of HoloLens. A calibration cube was 3d printed and the dual quaternion can serve as a quick calibration algorithm. An UWP is deployed into HoloLens which receives only real-time data and does not get involved in the computation.

***Screenshot of the navigation software under development:***
{% include image.html url="/images/software.jpg" caption="AR based Surgical Navigation Software" width=650 align="center" %}