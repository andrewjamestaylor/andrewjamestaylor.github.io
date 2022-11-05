---
title: Model Predictive Nonlinear Control
layout: splash
classes: wide

intro:
  - title: "Model Predictive Nonlinear Control"
    excerpt: TBD

feature_row_1:
  - image_path: assets/paper_materials/grandia2020nonlinear_model_predictive_control_of_robotic_systems_with_control_lyapunov_functions/wedding_cake.png
    title: "Nonlinear Model Predictive Control of Robotic Systems with Control Lyapunov Functions"
    excerpt: Ruben Grandia, <b>Andrew J. Taylor</b>, Andrew Singletary, Marco Hutter, and Aaron D. Ames, in <i>Proceedings of Robotics</i><i>:</i><i> Science and Systems XVI (RSS)</i>, Bend, OR, USA, 2020. <br> <br> <b>Abstract:</b> The theoretical unification of Nonlinear Model Predictive Control (NMPC) with Control Lyapunov Functions (CLFs) provides a framework for achieving optimal control performance while ensuring stability guarantees. In this paper we present the first real-time realization of a unified NMPC and CLF controller on a robotic system with limited computational resources. These limitations motivate a set of approaches for efficiently incorporating CLF stability constraints into a general NMPC formulation. We evaluate the performance of the proposed methods compared to baseline CLF and NMPC controllers with a robotic Segway platform both in simulation and on hardware. The addition of a prediction horizon provides a performance advantage over CLF based controllers, which operate optimally point-wise in time. Moreover, the explicitly imposed stability constraints remove the need for difficult cost function and parameter tuning required by NMPC. Therefore the unified controller improves the performance of each isolated controller and simplifies the overall design process.
    url: "assets/paper_materials/grandia2020nonlinear_model_predictive_control_of_robotic_systems_with_control_lyapunov_functions/paper.pdf"
    btn_label: "Paper"
    url2: "https://youtu.be/05ynUbpOD9o"
    btn_label2: "Presentation Video"
    url3: "assets/paper_materials/grandia2020nonlinear_model_predictive_control_of_robotic_systems_with_control_lyapunov_functions/presentation_slides.pdf"
    btn_label3: "Presentation Slides"

feature_row_2:
  - image_path: assets/images/hardware_trot_on_stones_wide_compressed.png
    title: "Multi-Layered Safety for Legged Robots via Control Barrier Functions and Model Predictive Control"
    excerpt: Ruben Grandia, <b>Andrew J. Taylor</b>, Aaron D. Ames, and Marco Hutter, in <i>Proceedings of the IEEE International Conference on Robotics and Automation (ICRA)</i>, Xi'an, China, 2021, pp. 8352-8358. <br> <br> <b>Abstract:</b> The problem of dynamic locomotion over rough terrain requires both accurate foot placement together with an emphasis on dynamic stability. Existing approaches to this problem prioritize immediate safe foot placement over longer term dynamic stability considerations, or relegate the coordination of foot placement and dynamic stability to heuristic methods. We propose a multi-layered locomotion framework that unifies Control Barrier Functions (CBFs) with Model Predictive Control (MPC) to simultaneously achieve safe foot placement and dynamic stability. Our approach incorporates CBF based safety constraints both in a low frequency kino-dynamic MPC formulation and a high frequency inverse dynamics tracking controller. This ensures that safety-critical execution is considered when optimizing locomotion over a longer horizon. We validate the proposed method in a 3D stepping-stone scenario in simulation and experimentally on the ANYmal quadruped platform.
    url: "assets/paper_materials/grandia2021multi_layered_safety_for_legged_robots_via_control_barrier_functions_and_model_predictive_control/paper.pdf"
    btn_label: "Paper"
    url2: "https://youtu.be/y_a_vJ1dJuQ"
    btn_label2: "Presentation Video"

feature_row_3:
  - image_path: assets/images/bezier_diagram.JPG
    title: "Multi-Rate Planning and Control of Uncertain Nonlinear Systems: Model Predictive Control and Control Lyapunov Functions"
    excerpt: Noel Csomay-Shanklin, <b>Andrew J. Taylor</b>, Ugo Rosolia, and Aaron D. Ames, in <i>Proceedings of the IEEE 61st Conference on Decision and Control (CDC)</i>, Cancún, Mexico, 2022. <br> <br> <b>Abstract:</b> Modern control systems must operate in increasingly complex environments subject to safety constraints and input limits, and are often implemented in a hierarchical fashion with different controllers running at multiple time scales. Yet traditional constructive methods for nonlinear controller synthesis typically ``flatten'' this hierarchy, focusing on a single time scale, and thereby limited the ability to make rigorous guarantees on constraint satisfaction that hold for the entire system. In this work we seek to address the stabilization of constrained nonlinear systems through a <i>multi-rate</i> control architecture. This is accomplished by iteratively planning continuous reference trajectories for a nonlinear system using a linearized model and Model Predictive Control (MPC), and tracking said trajectories using the full-order nonlinear model and Control Lyapunov Functions (CLFs). Connecting these two levels of control design in a way that ensures constraint satisfaction is achieved through the use of <i>Bézier curves</i>, which enable planning continuous trajectories respecting constraints by planning a sequence of discrete points. Our framework is encoded via convex optimization problems which may be efficiently solved, as demonstrated in simulation.
    url: "assets/paper_materials/csomayshanklin2022multirate_planning_and_control_of_uncertain_nonlinear_systems_model_predictive_control_and_control_lyapunov_functions/paper.pdf"
    btn_label: "Paper"

feature_row_4:
  - image_path: assets/paper_materials/galliker2022planar_bipedal_locomotion_with_nonlinear_model_predictive_control_online_gait_generation_using_whole_body_dynamics/Fig1.jpg
    title: "Bipedal Locomotion with Nonlinear Model Predictive Control: Online Gait Generation using Whole-Body Dynamics"
    excerpt: Manuel Y. Galliker, Noel Csomay-Shanklin, Ruben Grandia, <b>Andrew J. Taylor</b>, Farbod Farshidian, Marco Hutter, and Aaron D. Ames, in <i>Proceedings of the IEEE-RAS Conference on Humanoid Robots (Humanoids)</i>, Ginowan, Okinawa, Japan 2022. <br> <br> <b>Abstract:</b> The ability to generate dynamic walking in real-time for bipedal robots with input constraints and underactuation has the potential to enable locomotion in dynamic, complex and unstructured environments. Yet, the high-dimensional nature of bipedal robots has limited the use of full-order rigid body dynamics to gaits which are synthesized offline and then tracked online. In this work we develop an online nonlinear model predictive control approach that leverages the full-order dynamics to realize diverse walking behaviors. Additionally, this approach can be coupled with gaits synthesized offline via a desired reference to enable a shorter prediction horizon and rapid online re-planning, bridging the gap between online reactive control and offline gait planning. We demonstrate the proposed method, both with and without an offline gait, on the planar robot AMBER-3M in simulation and on hardware.
    url: "assets/paper_materials/galliker2022planar_bipedal_locomotion_with_nonlinear_model_predictive_control_online_gait_generation_using_whole_body_dynamics/paper.pdf"
    btn_label: "Paper"
---

{% include feature_row id = "intro" type = "center" %}

{% include feature_row id = "feature_row_4" type = "left" %}

{% include feature_row id = "feature_row_3" type = "left" %}

{% include feature_row id = "feature_row_2" type = "left" %}

{% include feature_row id = "feature_row_1" type = "left" %}
