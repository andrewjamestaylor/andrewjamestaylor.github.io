---
title: Discrete-Event Control
layout: splash
classes: wide

intro:
  - title: "Discrete-Event Control"
    excerpt: TBD

feature_row_1:
  - image_path: assets/paper_materials/taylor2020safety_critical_event_triggered_control_via_input_to_state_safe_barrier_functions/cex_both.png
    title: "Safety-Critical Event-Triggered Control via Input-to-State Safe Barrier Functions"
    excerpt: <b>Andrew J. Taylor</b>, Pio Ong, Jorge Cortés, and Aaron D. Ames, <i>IEEE Control Systems Letters</i>, vol. 5, no. 3, pp. 749-754, 2021. <br> <br> <b>Abstract:</b> The efficient utilization of available resources while simultaneously achieving control objectives is a primary motivation in the event-triggered control paradigm. In many modern control applications, one such objective is enforcing the safety of a system. The goal of this paper is to carry out this vision by combining event-triggered and safety-critical control design. We discuss how a direct transcription, in the context of safety, of event-triggered methods for stabilization may result in designs that are not implementable on real hardware due to the lack of a minimum interevent time. We provide an example showing this phenomena and, building on the insight gained,  propose an event-triggered control approach via Input-to-State Safe Barrier Functions that achieves safety while ensuring that interevent times are uniformly lower bounded.
    url: "assets/paper_materials/taylor2020safety_critical_event_triggered_control_via_input_to_state_safe_barrier_functions/paper.pdf"
    btn_label: "Paper"
    url2: "https://youtu.be/hSEkHc8wFn4"
    btn_label2: "Presentation Video"
    url3: "assets/paper_materials/taylor2020safety_critical_event_triggered_control_via_input_to_state_safe_barrier_functions/presentation_slides.pdf"
    btn_label3: "Presentation Slides"

feature_row_2:
  - image_path: assets/images/sampled_data_clf_controller_profiles.png
    title: "Sampled-Data Stabilization with Control Lyapunov Functions via Quadratically Constrained Quadratic Programs"
    excerpt: <b>Andrew J. Taylor</b>, Victor D. Dorobantu, Yisong Yue, Paulo Tabuada, and Aaron D. Ames, <i>IEEE Control Systems Letters</i>, vol. 6, pp. 680-685, 2021. <br> <br> <b>Abstract:</b> Controller design for nonlinear systems with Control Lyapunov Function (CLF) based quadratic programs has recently been successfully applied to a diverse set of difficult control tasks. These existing formulations do not address the gap between design with continuous time models and the discrete time sampled implementation of the resulting controllers, often leading to poor performance on hardware platforms. We propose an approach to close this gap by synthesizing sampled-data counterparts to these CLF-based controllers, specified as quadratically constrained quadratic programs (QCQPs). Assuming feedback linearizability and stable zero-dynamics of a system's continuous time model, we derive practical stability guarantees for the resulting sampled-data system. We demonstrate improved performance of the proposed approach over continuous time counterparts in simulation.
    url: "assets/paper_materials/taylor2021sampled_data_stabilization_with_control_lyapunov_functions_via_quadratically_constrained_quadratic_programs/paper.pdf"
    btn_label: "Paper"
    url2: "https://youtu.be/KybnikDRMUM"
    btn_label2: "Presentation Video"
    url3: "assets/paper_materials/taylor2021sampled_data_stabilization_with_control_lyapunov_functions_via_quadratically_constrained_quadratic_programs/presentation_slides.pdf"
    btn_label3: "Presentation Slides"

feature_row_3:
  - image_path: assets/paper_materials/taylor2022safety_of_sampled_data_systems_with_control_barrier_functions_via_approximate_discrete_time_models/ProofFigure.png
    title: "Safety of Sampled-Data Systems with Control Barrier Functions via Approximate Discrete Time Models"
    excerpt: <b> Andrew J. Taylor</b>, Victor D. Dorobantu, Ryan K. Cosner, Yisong Yue, and Aaron D. Ames, in <i>Proceedings of the IEEE 61st Conference on Decision and Control (CDC)</i>, Cancún, Mexico, 2022. <br> <br> <b>Abstract:</b> Control Barrier Functions (CBFs) have been demonstrated to be powerful tools for safety-critical controller design for nonlinear systems. Existing CBF-based design paradigms do not address the gap between theory (controller design with continuous time models) and practice (the discrete time sampled implementation of the resulting controllers); this can lead to poor closed-loop behavior and violations of safety for hardware instantiations.  We propose an approach to close this gap by synthesizing sampled-data counterparts to these CBF-based controllers using approximate discrete time models and <i>Sampled-Data Control Barrier Functions (SD-CBFs)</i>. Using properties of a system's continuous time model, we establish a relationship between SD-CBFs and a notion of <i>practical safety</i> for sampled-data systems. Furthermore, we construct convex optimization-based controllers that formally endow nonlinear systems with safety guarantees in practice. We demonstrate the efficacy of these controllers in simulation.
    url: "assets/paper_materials/taylor2022safety_of_sampled_data_systems_with_control_barrier_functions_via_approximate_discrete_time_models/paper.pdf"
    btn_label: "Paper"
---

{% include feature_row id = "intro" type = "center" %}

{% include feature_row id = "feature_row_3" type = "left" %}

{% include feature_row id = "feature_row_2" type = "left" %}

{% include feature_row id = "feature_row_1" type = "left" %}
