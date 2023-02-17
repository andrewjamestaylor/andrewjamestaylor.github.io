---
title: "Research"
layout: splash
classes: wide

intro:
  - title: "Research Overview"
    excerpt: "My research has focused on two overarching challenges: designing
    <b>robust</b> controllers for systems with <b>uncertainty</b>, and
    constructing <b>hierarchical</b> control frameworks for complex nonlinear
    systems. The following categories highlight the different uncertainties and
    hierarchical control frameworks I have studied. Click the text links to see
    more about a specific research challenge and my work on the topic. A
    complete list of my publications and invited presentations may be found at
    the bottom of the page."

feature_row_1:
  - image_path: ../assets/images/safety_gait_tiles.png
    url : "/_pages/research_projects/machine_learning_control/"
    btn_label: "Machine Learning for Nonlinear Control"
    btn_class: btn btn--default btn--large
  - image_path: ../assets/images/hardware_trot_on_stones_wide_compressed.png
    url : "/_pages/research_projects/model_predictive_control/"
    btn_label: "Model Predictive Nonlinear Control"
    btn_class: btn btn--default btn--large
  - image_path: ../assets/images/sampled_data_clf_controller_profiles.png
    url : "/_pages/research_projects/discrete_event_control/"
    btn_label: "Discrete-Event Control"
    btn_class: btn btn--default btn--large
feature_row_2:
  - image_path: ../assets/images/truck.png
    url : "/_pages/research_projects/disturbance_robust_control/"
    btn_label: "Disturbance Robust Safety-Critical Control"
    btn_class: btn btn--default btn--large
  - image_path: ../assets/images/adaptive_lienard_system.png
    url : "/_pages/research_projects/adaptive_control/"
    btn_label: "Adaptive Control for Safety-Critical Systems"
    btn_class: btn btn--default btn--large
  - image_path: ../assets/images/mrcbf_segway_gait_tile_short.png
    url : "/_pages/research_projects/perception_robust_control/"
    btn_label: "Robust Perception-Based Control"
    btn_class: btn btn--default btn--large
feature_row_3:
  - image_path: ../assets/images/backstepping_unicycle_avoid.png
    url : "/_pages/research_projects/higher_order_control/"
    btn_label: "Safety-Critical Control for Higher-Order Systems"
    btn_class: btn btn--default btn--large
---

{% include feature_row id="intro" type="center" %}

{% include feature_row id="feature_row_1" %}

{% include feature_row id="feature_row_2" %}

{% include feature_row id="feature_row_3" type = "center" %}

<h1 align = "center"> Publications </h1>

<h2 align = "center"> Preprints </h2>

<p>
Ryan K. Cosner, Preston Culbertson, <b>Andrew J. Taylor</b>, Aaron D. Ames, "Robust Safety under Stochastic Uncertainty with Discrete-Time Control Barrier Functions", submitted to <i>Robotics: Sciences and Systems XIX (RSS)</i>, 2023. 
</p>

<p>
Kim P. Wabersich, <b>Andrew J. Taylor</b>, Jason J. Choi, K. Sreenath, Claire J. Tomlin, Aaron D. Ames, and Melanie N. Zeilinger, "Data-Driven Safety Filters: Hamilton-Jacobi Reachability, Control Barrier Functions, and Predictive Methods for Uncertain Systems", submitted to <i>IEEE Control Systems</i>, 2022.
</p>

<p>
Anil Alan, <b> Andrew J. Taylor </b>, Chaozhe R. He, Aaron D. Ames, and Gabor Orosz, "Control Barrier Functions and Input-to-State Safety with Application to Automated Vehicles", submitted to <i>IEEE Transactions on Control Systems Technology (TCST)</i>, 2022.
</p>

<h2 align = "center"> Journal Papers </h2>

<p>
Anil Alan, <b>Andrew J. Taylor</b>, Chaozhe R. He, Gabor Orosz, and Aaron D. Ames, "Safe Controller Synthesis with Tunable Input-to-State Safe Control Barrier Functions", <i>IEEE Control Systems Letter</i>, vol. 6, pp. 908-913, 2021.
</p>

<p>
<b>Andrew J. Taylor</b>, Victor D. Dorobantu, Yisong Yue, Paulo Tabuada, and Aaron D. Ames, "Sampled-Data Stabilization with Control Lyapunov Functions via Quadratically Constrained Quadratic Programs", <i>IEEE Control Systems Letters</i>, vol. 6, pp. 680-685, 2021.
</p>

<p>
<b>Andrew J. Taylor</b>, Andrew Singletary, Yisong Yue, and Aaron D. Ames, "A Control Barrier Perspective on Episodic Learning via Projection-to-State Safety", <i>IEEE Control Systems Letters</i>, vol. 5, no.3, pp. 1029-1024, 2021.
</p>

<p>
<b>Andrew J. Taylor</b>, Pio Ong, Jorge Cortés, and Aaron D. Ames, "Safety-Critical Event-Triggered Control via Input-to-State Safe Barrier Functions", <i>IEEE Control Systems Letters</i>, vol. 5, no. 3, pp. 749-754, 2021.
</p>

<h2 align = "center"> Conference Papers </h2>

<p>
Manuel Y. Galliker, Noel Csomay-Shanklin, Ruben Grandia, <b>Andrew J. Taylor</b>, Farbod Farshidian, Marco Hutter, and Aaron D. Ames, "Bipedal Locomotion with Nonlinear Model Predictive Control: Online Gait Generation using Whole-Body Dynamics", in <i>Proceedings of the IEEE-RAS Conference on Humanoid Robots (Humanoids)</i>, Ginowan, Okinawa, Japan 2022.
</p>

<p>
<b>Andrew J. Taylor</b>, Pio Ong, Tamas G. Molnár, and Aaron D. Ames, "Safe Backstepping with Control Barrier Functions", in <i>Proceedings of the IEEE 61st Conference on Decision and Control (CDC)</i>, Cancún, Mexico, 2022.
</p>

<p>
Noel Csomay-Shanklin, <b>Andrew J. Taylor</b>, Ugo Rosolia, and Aaron D. Ames, "Multi-Rate Planning and Control of Uncertain Nonlinear Systems: Model Predictive Control and Control Lyapunov Functions", in <i>Proceedings of the IEEE 61st Conference on Decision and Control (CDC)</i>, Cancún, Mexico, 2022.
</p>

<p>
<b> Andrew J. Taylor</b>, Victor D. Dorobantu, Ryan K. Cosner, Yisong Yue, and Aaron D. Ames, "Safety of Sampled-Data Systems with Control Barrier Functions via Approximate Discrete Time Models", in <i>Proceedings of the IEEE 61st Conference on Decision and Control (CDC)</i>, Cancún, Mexico, 2022.
</p>

<p>
Ryan K. Cosner, Maegan Tucker, <b>Andrew J. Taylor</b>, Kejun Li, Tamas G. Molnár, Wyatt Ubellacker, Anil Alan, Gabor Orosz, Yisong Yue, and Aaron D. Ames, "Safety-Aware Preference-Based Learning for Safety-Critical Control", in <i>Proceedings of the 4th Conference on Learning for Dynamics and Control (L4DC)</i>, Palo Alto, CA, USA, 2022, pp. 1020-1033.
</p>

<p>
<b>Andrew J. Taylor</b>, Victor D. Dorobantu, Sarah Dean, Benjamin Recht, Yisong Yue, and Aaron D. Ames, "Towards Robust Data-Driven Control Synthesis for Nonlinear Systems with Actuation Uncertainty", in <i>Proceedings of the IEEE 60th Conference on Decision and Control (CDC)</i>, Austin, TX, USA, 2021, pp. 6469-6476.
</p>

<p>
Ryan K. Cosner, Andrew W. Singletary, <b>Andrew J. Taylor</b>, Tamas G. Molnár, Katherine L. Bouman, and Aaron D. Ames, "Measurement-Robust Control Barrier Functions: Certainty in Safety with Uncertainty in State", in <i>Proceedings of the IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)</i>, Prague, Czech Republic, 2021, pp.6286-6291.
</p>

<p>
Noel Csomay-Shanklin, Ryan K. Cosner, Min Dai, <b>Andrew J. Taylor</b>, and Aaron D. Ames, "Episodic Learning for Safe Bipedal Locomotion with Control Barrier Functions and Projection-to-State Safety", in <i>Proceedings of the 3rd Conference on Learning for Dynamics and Control (L4DC)</i>, Zürich, Switzerland, 2021, pp. 1041-1053.
</p>

<p>
Ruben Grandia, <b>Andrew J. Taylor</b>, Aaron D. Ames, and Marco Hutter, "Multi-Layered Safety for Legged Robots via Control Barrier Functions and Model Predictive Control", in <i>Proceedings of the IEEE International Conference on Robotics and Automation (ICRA)</i>, Xi'an, China, 2021, pp. 8352-8358.
</p>

<p>
Mohamed Maghenem, <b>Andrew J. Taylor</b>, Aaron D. Ames, and Ricardo G. Sanfelice, "Adaptive Safety Using Control Barrier Functions and Hybrid Adaption", in <i>Proceedings of the IEEE American Control Conference (ACC)</i>, New Orleans, LA, USA, 2021, pp. 2418-2423.
</p>

<p>
Sarah Dean, <b>Andrew J. Taylor</b>, Ryan K. Cosner, Benjamin Recht, and Aaron D. Ames, "Guaranteeing Safety of Learned Perception Modules via Measurement-Robust Control Barrier Functions", in <i>Proceedings of the 4th Conference on Robotics Learning (CoRL)</i>, Boston, MA, USA, 2020.
</p>

<p>
Ruben Grandia, <b>Andrew J. Taylor</b>, Andrew Singletary, Marco Hutter, and Aaron D. Ames, "Nonlinear Model Predictive Control of Robotic Systems with Control Lyapunov Functions", in <i>Proceedings of Robotics: Science and Systems XVI (RSS)</i>, Bend, OR, USA, 2020.
</p>

<p>
<b>Andrew J. Taylor</b>, Andrew Singletary, Yisong Yue, and Aaron D. Ames, "Learning for Safety-Critical Control with Control Barrier Functions", in <i>Proceedings of the 2nd Conference on Learning for Dynamics and Control (L4DC)</i>, Berkeley, CA, USA, 2020, pp. 708-717.
</p>

<p>
<b>Andrew J. Taylor</b> and Aaron D. Ames, "Adaptive Safety with Control Barrier Functions", in <i>Proceedings of the IEEE American Control Conference (ACC)</i>, Denver, CO, USA, 2020, pp. 1399-1405.
</p>

<p>
<b>Andrew J. Taylor</b>, Victor D. Dorobantu, Meera Krishnamoorthy, Hoang M. Le, Yisong Yue, and Aaron D. Ames, "A Control Lyapunov Perspective on Episodic Learning via Projection to State Stability", in <i>Proceedings of the IEEE 58th Conference on Decision and Control (CDC)</i>, Nice, France, 2019, pp. 1448-1455.
</p>

<p>
<b>Andrew J. Taylor</b>, Victor D. Dorobantu, Hoang M. Le, Yisong Yue, and Aaron D. Ames, "Episodic Learning with Control Lyapunov Functions for Uncertain Robotic Systems", in <i>Proceedings of the IEEE/RSJ International Conference on Intelligent Robotics and Systems (IROS)</i>, Macau, China, 2019, pp. 6878-6884.
</p>

<h1 align = "center">Invited Presentations</h1>

Sarah Dean, <b> Andrew Taylor</b>, "Towards Certifiably Safe Nonlinear Control with Sensor and Dynamics Uncertainties", <i>NeurIPS 5th Robot Learning Workshop: Trustworthy Robotics</i>, [Recorded Presentation](https://youtu.be/v_707BM1mwE), 2022.
<br>

<b>Andrew J. Taylor</b>, "A Control Lyapunov Function Approach to Episodic Learning", <i>1st Conference on Learning for Dynamics and Control (L4DC)</i>, Poster Presentation, 2019.
