---
title: Machine Learning for Nonlinear Control
layout: splash
classes: wide

intro:
  - title: "Machine Learning for Nonlinear Control"
    excerpt: "Designing model-based controllers for real-world systems is
              regularly complicated by imperfections in the system model, known
              as <b>model uncertainty</b>. Recent advances in the field of
              machine learning have enabled <b>data-driven</b> methods for
              reducing model uncertainty. My work has sought to rigorously unify
              techniques for safety-critical control with tools from machine
              learning with the goal of producing robust yet performant control
              designs that I can demonstrate on robotic systems."

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

feature_row_4:
  - image_path: assets/paper_materials/taylor2021control_barrier_perspective_on_episodic_learning_via_projection_to_state_safety/pssf.png
    title: "A Control Barrier Perspective on Episodic Learning via Projection-to-State Safety"
    excerpt: <b>Andrew J. Taylor</b>, Andrew Singletary, Yisong Yue, and Aaron D. Ames, <i>IEEE Control Systems Letters</i>, vol. 5, no.3, pp. 1029-1024, 2021. <br> <br> <b>Abstract:</b>  In this paper we seek to quantify the ability of learning to improve safety guarantees endowed by Control Barrier Functions (CBFs). In particular, we investigate how model uncertainty in the time derivative of a CBF can be reduced via learning, and how this leads to stronger statements on the safe behavior of a system. To this end, we build upon the idea of Input-to-State Safety (ISSf) to define Projection-to-State Safety (PSSf), which characterizes degradation in safety in terms of a projected disturbance. This enables the direct quantification of both how learning can improve safety guarantees, and how bounds on learning error translate to bounds on degradation in safety. We demonstrate that a practical episodic learning approach can use PSSf to reduce uncertainty and improve safety guarantees in simulation and experimentally.
    url: "assets/paper_materials/taylor2021control_barrier_perspective_on_episodic_learning_via_projection_to_state_safety/paper.pdf"
    btn_label: "Paper"
    url2: "https://youtu.be/rGUbBtFROsQ"
    btn_label2: "Presentation Video"
    url3: "assets/paper_materials/taylor2021control_barrier_perspective_on_episodic_learning_via_projection_to_state_safety/presentation_slides.pdf"
    btn_label3: "Presentation Slides"

feature_row_5:
  - image_path: assets/images/safety_gait_tiles.png
    title: "Episodic Learning for Safe Bipedal Locomotion with Control Barrier Functions and Projection-to-State Safety"
    excerpt: Noel Csomay-Shanklin, Ryan K. Cosner, Min Dai, <b>Andrew J. Taylor</b>, and Aaron D. Ames, in <i>Proceedings of the 3rd Conference on Learning for Dynamics and Control (L4DC)</i>, Zürich, Switzerland, 2021, pp. 1041-1053. <br> <br> <b>Abstract:</b>  This paper combines episodic learning and control barrier functions in the setting of bipedal locomotion. The safety guarantees that control barrier functions provide are only valid with perfect model knowledge; however, this assumption cannot be met on hardware platforms. To address this, we utilize the notion of projection-to-state safety paired with a machine learning framework in an attempt to learn the model uncertainty as it affects the barrier functions. The proposed approach is demonstrated both in simulation and on hardware for the AMBER-3M bipedal robot in the context of the stepping-stone problem, which requires precise foot placement while walking dynamically.
    url: "assets/paper_materials/csomayshanklin2021episodic_learning_for_safe_bipedal_locomotion_with_control_barrier_functions_and_projection_to_state_safety/paper.pdf"
    btn_label: "Paper"
    url2: "https://youtu.be/SZCxjRFaiQ0"
    btn_label2: "Presentation Video"
    url3: "assets/paper_materials/csomayshanklin2021episodic_learning_for_safe_bipedal_locomotion_with_control_barrier_functions_and_projection_to_state_safety/presentation_poster.pdf"
    btn_label3: "Presentation Poster"

feature_row_6:
  - image_path: assets/paper_materials/taylor2021towards_robust_data_driven_control_synthesis_for_nonlinear_systems_with_actuation_uncertainty/feasible_set.png
    title: "Towards Robust Data-Driven Control Synthesis for Nonlinear Systems with Actuation Uncertainty"
    excerpt: <b>Andrew J. Taylor</b>, Victor D. Dorobantu, Sarah Dean, Benjamin Recht, Yisong Yue, and Aaron D. Ames, in <i>Proceedings of the IEEE 60th Conference on Decision and Control (CDC)</i>, Austin, TX, USA, 2021, pp. 6469-6476. <br> <br> <b>Abstract:</b>  Modern nonlinear control theory seeks to endow systems with properties such as stability and safety, and has been deployed successfully across various domains. Despite this success, model uncertainty remains a significant challenge in ensuring that model-based controllers transfer to real world systems. This paper develops a data-driven approach to robust control synthesis in the presence of model uncertainty using Control Certificate Functions (CCFs), resulting in a convex optimization based controller for achieving properties like stability and safety. An important benefit of our framework is nuanced data-dependent guarantees, which in principle can yield sample-efficient data collection approaches that need not fully determine the input-to-state relationship. This work serves as a starting point for addressing important questions at the intersection of nonlinear control theory and non-parametric learning, both theoretical and in application. We demonstrate the efficiency of the proposed method with respect to input data in simulation with an inverted pendulum in multiple experimental settings.
    url: "assets/paper_materials/taylor2021towards_robust_data_driven_control_synthesis_for_nonlinear_systems_with_actuation_uncertainty/paper.pdf"
    btn_label: "Paper"
    url2: "https://youtu.be/tP5TNUxV1rg"
    btn_label2: "Presentation Video"
    url3: "assets/paper_materials/taylor2021towards_robust_data_driven_control_synthesis_for_nonlinear_systems_with_actuation_uncertainty/presentation_slides.pdf"
    btn_label3: "Presentation Slides"

feature_row_7:
  - image_path: assets/paper_materials/cosner2022safety_aware_preference_based_learning_for_safety_critical_control/quad_obstacles.png
    title: "Safety-Aware Preference-Based Learning for Safety-Critical Control"
    excerpt: Ryan K. Cosner, Maegan Tucker, <b>Andrew J. Taylor</b>, Kejun Li, Tamas G. Molnár, Wyatt Ubellacker, Anil Alan, Gabor Orosz, Yisong Yue, and Aaron D. Ames, in <i>Proceedings of the 4th Conference on Learning for Dynamics and Control (L4DC)</i>, Palo Alto, CA, USA, 2022, pp. 1020-1033. <br> <br> <b>Abstract:</b>  Bringing dynamic robots into the wild requires a tenuous balance between performance and safety. Yet controllers designed to provide robust safety guarantees often result in conservative behavior, and tuning these controllers to find the ideal trade-off between performance and safety typically requires domain expertise or a carefully constructed reward function. This work presents a design paradigm for systematically achieving behaviors that balance performance and robust safety by integrating <i>safety-aware</i> Preference-Based Learning (PBL) with Control Barrier Functions (CBFs). Fusing these concepts---safety-aware learning and safety-critical control---gives a robust means to achieve safe behaviors on complex robotic systems in practice. We demonstrate the capability of this design paradigm to achieve safe and performant perception-based autonomous operation of a quadrupedal robot both in simulation and experimentally on hardware.
    url: "assets/paper_materials/cosner2022safety_aware_preference_based_learning_for_safety_critical_control/paper.pdf"
    btn_label: "Paper"
    url2: "https://youtu.be/YOFyMqK_WL8"
    btn_label2: "Presentation Video"
    url3: "assets/paper_materials/cosner2022safety_aware_preference_based_learning_for_safety_critical_control/presentation_poster.pdf"
    btn_label3: "Presentation Poster"

feature_row_8:
  - image_path: assets/paper_materials/wabersich2022data_driven_safety_filters_hamilton_jacobi_reachability_control_barrier_functions_and_predictive_methods_for_uncertain_systems/safety_overview.png
    title: "Data-Driven Safety Filters: Hamilton-Jacobi Reachability, Control Barrier Functions, and Predictive Methods for Uncertain Systems"
    excerpt: Kim P. Wabersich, <b>Andrew J. Taylor</b>, Jason J. Choi, K. Sreenath, Claire J. Tomlin, Aaron D. Ames, and Melanie N. Zeilinger, submitted to <i>IEEE Control Systems</i>, 2022. <br> <br> <b>Summary:</b> Some of the most challenging problems in control typically consist of minimizing an objective function under safety constraints and physical limitations. These often conflicting requirements render classical stabilization-based control design tricky, and even modern learning-based alternatives rarely provide strict safety guarantees `out-of-the-box'. Safety filters address this limitation through a modular approach to safety. The first part of this article formalizes an ideal safety filter to enhance any controller with safety guarantees and provides a tutorial-style exposition of invariance-based methods using Hamilton-Jacobi reachability, control barrier functions, and predictive control related techniques. While the first part assumes perfect knowledge of the system dynamics, the second part bridges the gap toward real-world applications through data-driven model corrections. To this end, deterministic-, robust-, and probabilistic model learning techniques are outlined, and a selection of mini-tutorials for learning-based safety filters is provided. The article concludes with recent applications to demonstrate the capability of various safety filter formulations when combined with stabilizing controllers, learning-based controllers, and even humans.
    url: "assets/paper_materials/wabersich2022data_driven_safety_filters_hamilton_jacobi_reachability_control_barrier_functions_and_predictive_methods_for_uncertain_systems/preprint.pdf"
    btn_label: "Preprint"
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
