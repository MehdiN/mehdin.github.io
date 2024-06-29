---
title: "Simultaneous Pose and Posture Estimation with a Two-stage Particle Filter for Visuo-inertial Fusion"
collection: publications
permalink: /publication/2024-02-17-paper-title-number-4
# excerpt: 'This paper is about fixing template issue #693.'
date: 2022-07-01
venue: '2022 International Conference on Advanced Robotics and Mechatronics'
paperurl: 'https://ieeexplore.ieee.org/document/9959293'
citation: 'N. Mehdi, V. Thomas, S. Ivaldi and F. Colas &quot;Simultaneous Pose and Posture Estimation with a Two-stage Particle Filter for Visuo-inertial Fusion.&quot; <i>2022 International Conference on Advanced Robotics and Mechatronics (ICARM)</i>.'
---

We address the problem of human pose and posture estimation without any high precision marker-based motion capture
systems, by merging inertial data from wearable sensors and a single RGB camera.
Our proposition is based on a biomechanical model of the human body and two coupled filters:
the first filter takes advantage of the accurate posture observations provided by wearable sensors 
and a factorization of joints to estimate the human posture with a reduced number of particles 
while the second filter uses RGB camera observations to estimate the drift of the wearable sensor 
so as to estimate the global state (pose and posture). 
In order to combine those filters, the estimated human posture distribution of the first filter 
is used as a proposal distribution for the second fusion filter so as to focus on particles with 
an already high-likelihood posture and to improve the efficiency of the pose estimation. 
Results showed this approach can perform online estimation of the human posture and 
the human pose (through the drift of the wearable sensor) and performed better than techniques
relying only on inertial sensor or on direct pose estimation.
