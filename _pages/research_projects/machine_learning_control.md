---
title: Machine Learning for Nonlinear Control
layout: splash
classes: wide

intro:
  - title: "Machine Learning for Nonlinear Control"
    excerpt: TBD

feature_row_1:
  - image_path: assets/paper_materials/taylor2019episodic_learning_with_control_lyapunov_functions_for_uncertain_robotic_systems/episodic_learning.png
    title: "Episodic Learning with Control Lyapunov Functions for Uncertain Robotic Systems"
    excerpt: <b>Andrew J. Taylor</b>, Victor D. Dorobantu, Hoang M. Le, Yisong Yue, and Aaron D. Ames, in <i>Proceedings of the IEEE/RSJ International Conference on Intelligent Robotics and Systems (IROS)</i>, Macau, China, 2019, pp. 6878-6884. <br> <br> <b>Abstract:</b> Many modern nonlinear control methods aim to endow systems with guaranteed properties, such as stability or safety, and have been successfully applied to the domain of robotics. However, model uncertainty remains a persistent challenge, weakening theoretical guarantees and causing implementation failures on physical systems. This paper develops a machine learning framework centered around Control Lyapunov Functions (CLFs) to adapt to parametric uncertainty and unmodeled dynamics in general robotic systems. Our proposed method proceeds by iteratively updating estimates of Lyapunov function derivatives and improving controllers, ultimately yielding a stabilizing quadratic program model-based controller. We validate our approach on a planar Segway simulation, demonstrating substantial performance improvements by iteratively refining on a base model-free controller.
    url: "assets/paper_materials/taylor2019episodic_learning_with_control_lyapunov_functions_for_uncertain_robotic_systems/paper.pdf"
    btn_label: "Paper"
    url2: "https://youtu.be/cB5MY_8vCrQ"
    btn_label2: "Supplemental Video"
    url3: "assets/paper_materials/taylor2019episodic_learning_with_control_lyapunov_functions_for_uncertain_robotic_systems/presentation_slides.pdf"
    btn_label3: "Presentation Slides"

feature_row_2:
  - image_path: assets/paper_materials/taylor2019control_lyapunov_perspective_on_episodic_learning_via_projection_to_state_stability/heatmaps.png
    title: "A Control Lyapunov Perspective on Episodic Learning via Projection to State Stability"
    excerpt: "<b>Andrew J. Taylor</b>, Victor D. Dorobantu, Meera Krishnamoorthy, Hoang M. Le, Yisong Yue, and Aaron D. Ames, in <i>Proceedings of the IEEE 58th Conference on Decision and Control (CDC)</i>, Nice, France, 2019, pp. 1448-1455. <br> <br> <b>Abstract:</b> The goal of this paper is to understand the impact of learning on control synthesis from a Lyapunov function perspective.  In particular, rather than consider uncertainties in the full system dynamics, we employ Control Lyapunov Functions (CLFs) as low-dimensional projections. To understand and characterize the uncertainty that these projected dynamics introduce in the system, we introduce a new notion: Projection to State Stability (PSS). PSS can be viewed as a variant of Input to State Stability defined on projected dynamics, and enables characterizing  robustness of a CLF with respect to the data used to learn system uncertainties. We use PSS to bound uncertainty in affine control, and demonstrate that a practical episodic learning approach can use PSS to characterize uncertainty in the CLF for robust control synthesis."
    url: "assets/paper_materials/taylor2019control_lyapunov_perspective_on_episodic_learning_via_projection_to_state_stability/paper.pdf"
    btn_label: "Paper"
    url2: "assets/paper_materials/taylor2019control_lyapunov_perspective_on_episodic_learning_via_projection_to_state_stability/presentation_slides.pdf"
    btn_label2: "Presentation Slides"

feature_row_3:
  - image_path: assets/paper_materials/taylor2020learning_for_safety_critical_control_with_control_barrier_functions/segway_hardware.png
    title: "Learning for Safety-Critical Control with Control Barrier Functions"
    excerpt: <b>Andrew J. Taylor</b>, Andrew Singletary, Yisong Yue, and Aaron D. Ames, in <i>Proceedings of the 2nd Conference on Learning for Dynamics and Control (L4DC)</i>, Berkeley, CA, USA, 2020, pp. 708-717. <br> <br> <b>Abstract:</b>  Modern nonlinear control theory seeks to endow systems with properties of stability and safety, and have been deployed successfully in multiple domains. Despite this success, model uncertainty remains a significant challenge in synthesizing safe controllers, leading to degradation in the properties provided by the controllers. This paper develops a machine learning framework utilizing Control Barrier Functions (CBFs) to reduce model uncertainty as it impact the safe behavior of a system. This approach iteratively collects data and updates a controller, ultimately achieving safe behavior. We validate this method in simulation and experimentally on a Segway platform.
    url: "assets/paper_materials/taylor2020learning_for_safety_critical_control_with_control_barrier_functions/paper.pdf"
    btn_label: "Paper"
    url2: "https://youtu.be/tD8zH4GF_8U"
    btn_label2: "Supplemental Simulation Video"
    url3: "https://youtu.be/YCesvD_Ae00"
    btn_label3: "Supplemental Hardware Video"
    url4: "assets/paper_materials/taylor2020learning_for_safety_critical_control_with_control_barrier_functions/presentation_poster.pdf"
    btn_label4: "Presentation Poster"
---

{% include feature_row id = "intro" type = "center" %}

{% include feature_row id = "feature_row_8" type = "left" %}

{% include feature_row id = "feature_row_7" type = "left" %}

{% include feature_row id = "feature_row_6" type = "left" %}

{% include feature_row id = "feature_row_5" type = "left" %}

{% include feature_row id = "feature_row_4" type = "left" %}

{% include feature_row id = "feature_row_3" type = "left" %}

{% include feature_row id = "feature_row_2" type = "left" %}

{% include feature_row id = "feature_row_1" type = "left" %}
