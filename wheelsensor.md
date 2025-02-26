---
layout: project
type: project
image: projects/wheelsensor-ICS496/img/polarization-process.png
title: "In-wheel Polarization Camera Sensor"
date: 2025
published: true
labels:
  - Polarization
  - Neural Networks
  - Terramechanics
summary: "Developing a prototype for a polarimetric terramechanic wheel sensor."
---

# ICS 496 Capstone Project - UH Manoa S25
## Project Team

- **Kai Garcia**: Hardware Design & Data Pipeline <a href="https://github.com/KaiGarcia" target="_blank" rel="noopener noreferrer">GitHub Profile</a>
- **Mairi Yoshioka**: Machine Learning & Software <a href="https://github.com/mair1" target="_blank" rel="noopener noreferrer">GitHub Profile</a>

<figure>
  <a href="https://arxiv.org/pdf/2112.11377" target="_blank">
    <img src="/projects/wheelsensor-ICS496/img/polarization-process.png" alt="Polarization Process" style="width: 100%;">
  </a>
  <figcaption>
    Figure 1: Polarization Process. Source: <a href="https://arxiv.org/pdf/2112.11377" target="_blank">Shape from Polarization for Complex Scenes in the Wild</a>.
  </figcaption>
</figure>

## Project Details

*Polarimetric Wheel Terramechanic Sensor*

**End Goal:** Deliver a working prototype of a polarimetric terramechanic wheel sensor.

**System Components:**

1. Polarization camera and light mounted inside the wheel
2. Neural network for data processing

![Project Goal](/projects/wheelsensor-ICS496/img/project-goal.png){: width="50%"}

## Weekly Summaries

**Week 1:**
- Established sponsor and student goals and expectations
- Introduced project details

**Week 2:**
- Conducted research on polarization and PyTorch

**Week 3 (2/5-2/12):**
- Set up the camera
- Downloaded the SFP-Wild model

**Week 4 (2/13-2/19):**
- Developed camera pipeline to NumPy
- Ran SFP-Wild model on example images

![Pipeline Result 1](/projects/wheelsensor-ICS496/img/pipe-test-result1.png){: width="50%"}

## About

This project is part of the ICS 496 Capstone Project, focusing on developing an in-wheel polarization camera sensor.

*Content sourced from the [wheelsensor-ICS496 repository](https://github.com/KaiGarcia/wheelsensor-ICS496).*

## Citations

1. Lei, C., Qi, C., Xie, J., Fan, N., Koltun, V., & Chen, Q. (2022). <a href="https://arxiv.org/pdf/2112.11377" target="_blank" rel="noopener noreferrer">Shape from Polarization for Complex Scenes in the Wild</a>. *Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)*, 12632-12641. <a href="https://github.com/ChenyangLEI/sfp-wild" target="_blank" rel="noopener noreferrer">[GitHub Repository]</a>
