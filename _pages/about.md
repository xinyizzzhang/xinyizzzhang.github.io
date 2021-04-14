---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---    
## Short Bio

I'm a Ph.D. student at [Harada Lab.](https://www.roboticmanipulation.org/) in [Osaka University](https://www.osaka-u.ac.jp/en), advised by [Professor Kensuke Harada](http://www.hlab.sys.es.osaka-u.ac.jp/people/harada/). My research interests include perception and planning for vision-based industrial picking under complex scenarios. I received my M.E. from Osaka University and B.E. from Tianjin University, China.


![avatar-w70](/images/frontpage.png)

<br>

## Research Topics

- Bin-picking strategies for complex physical phenomenon
  - Grasp planning for complex-shaped industrial parts
  - Motion Generation for separating entangled partrs

- Accuracy on vision-based bin-picking
  - Online error compensation



## Projects

-----------------

**Learning Motion for Separating Tangled Objects (Upgraded Verssion)**

<span style="font-size:90%;text-align:justify">In this work, <img align="right" width="30%" src="/images/shaking.gif">we solve the entanglemenet problem by not only tilting motion of gripper. We generate a combined action call shake-and-pull with pre-defined frequency and distance. A force sensor mounted on the wrist of robot arm. While the gripper with entangled obejcts is rising, proposed method predict whether if the shake-and-pull action should be executed. See this picture! </span> 

-----------------


**Learning Motion for Separating Tangled Objects**

In this work, we introduce an end-to-end learning network to predict tilting motion of gripper for the purpose of separating grasped and tangled objects. We trained a lightweight deep learning network to predict which orientation the gripper should tilt. The experimental result shows when the robot is holding several tangled objects, the generated motion can ensure the robot gets rid of other objects and keep one object in the gripper. 

-----------------

**Recognizing Entanlgement and Detecting Grasps for Randomized Bin-picking**

<img align="right" width="320" src="/images/emap.jpg">
This paper addresses the problem of picking up only one object at a time avoiding any entanglement in bin-picking. To cope with a difficult case where the complex-shaped objects are heavily entangled together, we propose a topology-based method that can generate non-tangle grasp positions on a single depth image. The core technique is entanglement map, which is a feature map to measure the entanglement possibilities obtained from the input image. We use entanglement map to select probable regions containing graspable objects. The optimum grasping pose is detected from the selected regions considering the collision between robot hand and objects. 

-----------------

**Online Error Commpensation for Randomized Bin-picking**

We presented a two-stage method to realize the error compensation for randomized bin-picking. We focus on the calibration error between sensor frame and the robot frame by gradually refining calibration matrix. Moreover, the compensation process can be done online every time robot picks up the parts so that the updated calibration matrix can be used for the next picking.

