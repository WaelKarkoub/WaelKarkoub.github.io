---
layout: archive
title: "Research Experience"
permalink: /research_experience/
author_profile: true
---

<span style="display:block;text-align:center"><img src = "/images/truck.jpg" width ="400" /> <img src = "/images/ddr.jpg" width ="400" /> </span>

## [SYSTEM IDENTIFICATION OF AUTONOMOUS ON AND OFF-ROAD VEHICLES WITH NON-LINEAR MODEL PREDICTIVE CONTROL FOR PATH TRACKING](/files/KARKOUB-THESIS-2021.pdf)

There is no question that autonomous vehicles and robots are going to have a profound impact on the society in the near future. A deep understanding of the systems is required in-order to design safe autonomous systems that are deployed among people. A nonlinear data-driven system iden-tification techniques was explored to improve the physics-based models coupled with a nonlinear MPC for path tracking for the Warthog and ASV. A novel approach for a longitudinal controller was also introduced for ASV. Domain knowledge was extensively used to generate a feature set for the machine learning algorithms to learn. During the experiment, it was found that for the Warthog dataset, it needed at least 103 seconds worth of data to outperform the physics-based model. No conclusion can be made regarding the generality of the model. The learned models, for both the Warthog and ASV, returned the physics-based model with the parameters identified, suggesting that there is a slight delay in the system that was not accounted for given the nominal values. The nonlinear MPCs were validated using the Gazebo and CARLA simulators. The MPC for the Warthog followed the predefined path with an average error of 8 cm, however, it struggled with sliding while turning. The MPC for the ASVs were tested using three different scenarios; highway exits and entrances, highway driving, and city driving. Both the lateral and the controller tracked the generated path within the safety margin, which is the lane width. However, it failed the city driving test, exceeding the cross-track error of 3 m.

<span style="display:block;text-align:center">[![IMAGE ALT TEXT](http://img.youtube.com/vi/8lQ_X2vMhOo/0.jpg)](http://www.youtube.com/watch?v=8lQ_X2vMhOo "Tesla at Exits Sim") [![IMAGE ALT TEXT](http://img.youtube.com/vi/dORc1rVnBLw/0.jpg)](http://www.youtube.com/watch?v=dORc1rVnBLw "Warthog path following")</span>

## [SYSTEM IDENTIFICATION OF AUTONOMOUS ON AND OFF-ROAD VEHICLES WITH NON-LINEAR MODEL PREDICTIVE CONTROL FOR PATH TRACKING](/files/Efficient_Traffic_Light_Detection_for_Autonomous_Vehicles.pdf)

Autonomous vehicles are quickly becoming a reality, expected to increase the safety and the efficiency of transportation infrastructure. One important factor of autonomous vehicles is their ability to detect traffic lights accurately at longer distances as they approach an intersection. We have developed an efficient algorithm based on XGBoost that is able to detect traffic lights as far as 45 m away from an intersection. We evaluated our algorithm on approximately 5000 frames, which were labeled according to their distances. The overall precision and recall were found to be 99.8% and 88.1%, respectively, and the algorithm can make the appropriate decision with 91% accuracy. The proposed algorithm can be executed on a CPU at 13 fps.

<p align="center">
  <img src="/images/tl_detection_arch.png" width=750>
</p>
