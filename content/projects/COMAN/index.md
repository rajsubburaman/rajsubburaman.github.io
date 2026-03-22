---
title: Controlled Fall with COMAN+ Humanoid
date: 2018-2019
#links:
#  - type: site
#    url: https://github.com/pandas-dev/pandas
#tags:
#  - Hugo
#  - HugoBlox
#  - Markdown
---

## Controlled Fall

<iframe width="700" height="400"
src="https://www.youtube.com/embed/EhVlBOKAByY"
frameborder="0"
allowfullscreen>
</iframe>

This video shows the controlled fall motion of the COMAN+ humanoid in the Gazebo simulator. The controlled fall motion in four major directions: forward, backward, left-side, and right-side are shown. The generated motion is more dynamic and it is similar to the Ukemi or parkour roll motions exhibited by trained humans. This controlled fall motion is generated using the rolling motion generation controller proposed in the paper given below:
*Subburaman, Rajesh, Nikos G. Tsagarakis, and Jinoh Lee. "Online rolling motion generation for humanoid falls based on active energy control concepts." 2018 IEEE-RAS 18th International Conference on Humanoid Robots (Humanoids). IEEE, 2018.*

### Multi-Modal State Estimate
<img src="/static/uploads/Cogimon_state.png" width="600">

A multi-modal state estimate is proposed by fusing the foot-pressure sensors, IMUs, and joint encoders (through forward kinematics) with an extended Kalman filter (EKF). This estimator gives not only position, velocity, and orientation of the base but also the orientation of the foot which is critical for successful execution of the above controlled fall motions in humanoids. In addition, the proposed state estimator can estimate the base accurately not just on flat terrains but also on uneven terrains. The picture shown above is an rviz visualization of the state estimator results. 