---
title: Adaptive Control for Safety-Critical Systems
layout: splash
classes: wide

intro:
  - title: "Adaptive Control for Safety-Critical Systems"
    excerpt: "Adaptive control is a classic tool for resolving parametric errors
              in a system model by estimating parameters online as a system evolves.
              My work has focused on extending these classical tools to the task
              of safety-critical control while understanding fundamental limits
              on safety in the face of parametric model error."

feature_row_1:
  - image_path: /assets/images/adaptive_lienard_system.png
    title: "Adaptive Safety with Control Barrier Functions"
    excerpt: <b>Andrew J. Taylor</b> and Aaron D. Ames, in <i>Proceedings of the IEEE American Control Conference (ACC)</i>, Denver, CO, USA, 2020, pp. 1399-1405. <br> <br> <b>Abstract:</b> Adaptive Control Lyapunov Functions (aCLFs) were introduced 20 years ago, and provided a Lyapunov-based methodology for stabilizing systems with parameter uncertainty. The goal of this paper is to revisit this classic formulation in the context of safety-critical control. This will motivate a variant of aCLFs in the context of safety<i>:</i> <i>adaptive Control Barrier Functions (aCBFs)</i>. Our proposed approach adaptively achieves safety by keeping the system's state within a safe set even in the presence of parametric model uncertainty. We unify aCLFs and aCBFs into a single control methodology for systems with uncertain parameters in the context of a Quadratic Program (QP) based framework. We validate the ability of this unified framework to achieve stability and safety in an Adaptive Cruise Control (ACC) simulation.
    url: "/assets/paper_materials/taylor2020adaptive_safety_with_control_barrier_functions/paper.pdf"
    btn_label: "Paper"
    url2: "https://youtu.be/WX9QCVx8cQw"
    btn_label2: "Presentation Video"
    url3: "/assets/paper_materials/taylor2020adaptive_safety_with_control_barrier_functions/presentation_slides.pdf"
    btn_label3: "Presentation Slides"

feature_row_2:
  - title: "Adaptive Safety Using Control Barrier Functions and Hybrid Adaptation"
    excerpt: Mohamed Maghenem, <b>Andrew J. Taylor</b>, Aaron D. Ames, and Ricardo G. Sanfelice, in <i>Proceedings of the IEEE American Control Conference (ACC)</i>, New Orleans, LA, USA, 2021, pp. 2418-2423. <br> <br> <b>Abstract:</b> This paper presents a hybrid adaptive law for safety-critical adaptive control of constrained continuous-time systems under the effect of unknown disturbances. The proposed adaptive law features a hybrid update law that, using a hysteresis-type mechanism, appropriately resets the estimate of the  disturbance. In contrast to continuous-time adaptation laws for safety-critical control, our hybrid adaptive law relaxes the assumption typically imposed on the unknown disturbances as well as the behavior usually imposed around the boundary of the safe region.  We illustrate the benefits of the proposed hybrid law in an adaptive cruise control problem.
    url: "/assets/paper_materials/maghenem2021adaptive_safety_using_control_barrier_functions_and_hybrid_adaptation/paper.pdf"
    btn_label: "Paper"
---

{% include feature_row id = "intro" type = "center" %}

{% include feature_row id = "feature_row_2" type = "left" %}

{% include feature_row id = "feature_row_1" type = "left" %}
