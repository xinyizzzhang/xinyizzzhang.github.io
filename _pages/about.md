---
permalink: /
title: "Short Bio"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---    
I'm a Ph.D. student at [Harada Lab.](https://www.roboticmanipulation.org/) in [Osaka University](https://www.osaka-u.ac.jp/en), advised by [Professor Kensuke Harada](http://www.hlab.sys.es.osaka-u.ac.jp/people/harada/). My research interests include perception and planning for vision-based industrial picking under complex scenarios. I received my M.E. from Osaka University and B.E. from Tianjin University, China. 

![avatar-w70](/images/frontpage.png)

# Research Topics
------

- **Topological Solution to Entanlgement of Industrial Parts**

A topology-based algorithm is designed to decide whether the parts are getting tangled or not. Also, another algorithm is proposed to generate the motion for solving entanglement.

- **Learning Motion for Separating Tangled Objects**

In this work, we introduce an end-to-end learning network to predict the orientation of gripper motion for the purpose of separating grasped and tangled objects. We trained a lightweight deep learning network to predict which orientation the gripper should tilt. The experimental result shows when the robot is holding several tangled objects, the generated motion can ensure the robot gets rid of other objects and keep one object in the gripper.

- **Online Error Commpensation for Randomized Bin-picking**

We presented a two-stage method to realize the error compensation for randomized bin-picking. We focus on the calibration error between sensor frame and the robot frame by gradually refining calibration matrix. Moreover, the compensation process can be done online every time robot picks up the parts so that the updated calibration matrix can be used for the next picking.


