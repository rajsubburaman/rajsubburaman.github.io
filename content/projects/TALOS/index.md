---
title: HoRoPo Project - Whole-Body MultiContact Manipulation [UnPublished Works]
date: 2026-03-29
#links:
#  - type: site
#    url: https://github.com/pandas-dev/pandas
#tags:
#  - Hugo
#  - HugoBlox
#  - Markdown
---

## HoRoPo Project: TALOS Humanoid

### Carton Box Lifting Experiment
<iframe width="700" height="400"
src="https://www.youtube.com/embed/dvt0N1KKFoc"
frameborder="0"
allowfullscreen>
</iframe>

The video shows the Talos humanoid grasping and lifting a large carton box using two forearm contacts. The motion is planned such that the contacts occur on skin patches attached to the humanoid's forearms. The complete motion is executed using a whole-body multicontact model predictive control framework (WBMC-MPC), solved in real time with a DDP-based solver. The humanoid is controlled in torque mode throughout the entire experiment.

### Carton Box Manipulation Experiment [Journal Publication in Progress]
<iframe width="700" height="400"
src="https://www.youtube.com/embed/JIccBCjknMI"
frameborder="0"
allowfullscreen>
</iframe>

This video shows the Talos humanoid manipulating a large carton box weighing 0.75kg using two forearm contacts. The manipulation involves the following phases: i)Approach, ii) Grasp, iii) Lift, iv)Manipulate, v) Drop, and vi) UnGrasp. Similar to the above experiment, the motion is realized using the WBMC-MPC controller in torque mode. The skin patch data are actively used inside the controller.

<iframe width="700" height="400"
src="https://www.youtube.com/embed/QX7-wfMnFRo"
frameborder="0"
allowfullscreen>
</iframe>

This shows the skin patch data collected during the manipulation experiment being relayed to RViz for real-time visualization. In particular, the following data are displayed: active skin cells (red), resultant absolute acceleration (magenta), and the resultant force acting at the corresponding location, represented in the contact frame (green).

*Journal publication is in progress with better experiments and results*

### EKF-based Object-Contact State Estimation [Journal Publication in Progress]

<iframe width="700" height="400"
src="https://www.youtube.com/embed/7LLgcj8oSso"
frameborder="0"
allowfullscreen>
</iframe>

An EKF-based object contact state estimator is proposed to estimate its evolution during the dynamic whole-body manipulation of an object. The proposed estimator can estimate the following variables: object pose, twist, contact pose, linear velocity, and contact wrench. The video shows the preliminary evaluation results of the estimator carried out with a manipulation data generated from the gazebo simulator. The green box represents the predicted pose and the blue color denotes its actual pose.

***People Involved:*** Rajesh Subburaman, Francesco Rachiglia, Olivier Stasse

*Journal publication is in progress with experiments and results*

### Object Dynamics-Aware Whole-Body Multicontact Manipulation [soon to be published]
The following videos shows the whole-body multicontact manipulation of heavy objects with its dynamics integrated into the WBMC-MPC controller. The evaluation of the proposed controller is carried out with the mujoco simulator. The skin patches attached to the Talos humanoid's upperbody are shown as rigid bodies (orange) with its contact dynamics simulated using the simulator's inbuilt contact sensor.

**Large Box - 2 contacts**
<iframe width="700" height="400"
src="https://www.youtube.com/embed/j3mCSX30yn0"
frameborder="0"
allowfullscreen>
</iframe>
Box weighing 5kg is being manipulated with two forearm contacts.

**Small Cylinder - 3 contacts**
<iframe width="700" height="400"
src="https://www.youtube.com/embed/_YRkp3b8dak"
frameborder="0"
allowfullscreen>
</iframe>
A small cylinder weighing 5kg is being manipulated here with three contacts (2-forearm, 1-torso). Since the object is slightly far from the torso, the robot pulls the object towards it with two forearm contacts and then grasps and lifts it with three contacts.

**Large Cylinder - 5 contacts**
<iframe width="700" height="400"
src="https://www.youtube.com/embed/Fpi1Z6JJ8yM"
frameborder="0"
allowfullscreen>
</iframe>

A large cylinder weighing 5kg is manipulated here with five contacts in total (2-forearm, 2-shoulder, 1-torso).

*The work will soon be published in a Conference/Journal with more details and additional evaluations.*

© 2026 Rajesh Subburaman. All rights reserved.

[![Creative Commons License](https://i.creativecommons.org/l/by-nc-nd/4.0/88x31.png)](https://creativecommons.org/licenses/by-nc-nd/4.0/)

This work is licensed under a [Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License](https://creativecommons.org/licenses/by-nc-nd/4.0/).