---
layout: project
type: project
image: projects/wheelsensor-ICS496/img/polarization-process.png
title: "Polarimetric Terra-mechanic Sensor"
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

![Polarization Process](/projects/wheelsensor-ICS496/img/polarization-process.png){: width="100%"}

_Figure 1: Neural Network Source. Adapted from [[1]](#cite-1)._

## Project Details

*Polarimetric Wheel Terramechanic Sensor*

**End Goal:** Deliver a working prototype of a polarimetric terramechanic wheel sensor.

**System Components:**

1. Polarization camera and light mounted inside the wheel
2. Neural network for data processing

![Project Goal](/projects/wheelsensor-ICS496/img/project-goal.png){: width="50%"}

_Figure 2: Conceptual diagram of a vision-based terrain traversability system using an in-wheel polarization camera. Adapted from [[2]](#cite-2)._

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

<a id="cite-1"></a> **[1]** Lei, C., Qi, C., Xie, J., Fan, N., Koltun, V., & Chen, Q. (2022). [Shape from Polarization for Complex Scenes in the Wild](https://arxiv.org/pdf/2112.11377). *Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)*, 12632-12641. [GitHub Repository](https://github.com/ChenyangLEI/sfp-wild)

<a id="cite-2"></a> **[2]** Kalra, A., Taamazyan, V., Rao, S. K., Venkataraman, K., Raskar, R., & Kadambi, A. (2020). *Deep polarization cues for transparent object segmentation*. *Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)*, 8602–8611.
