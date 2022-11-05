---
title: Robust Perception-Based Control
layout: splash
classes: wide

intro:
  - title: "Robust Perception-Based Control"
    excerpt: TBD

feature_row_1:
  - image_path: assets/paper_materials/dean2020guaranteeing_safety_of_learned_perception_modules_via_measurement_robust_control_barrier_functions/camera_feed_enhanced.png
    title: "Guaranteeing Safety of Learned Perception Modules via Measurement-Robust Control Barrier Functions"
    excerpt: Sarah Dean, <b>Andrew J. Taylor</b>, Ryan K. Cosner, Benjamin Recht, and Aaron D. Ames, in <i>Proceedings of the 4th Conference on Robotics Learning (CoRL)</i>, Boston, MA, USA, 2020. <br> <br> *Best Paper Nominee* <br> <br> <b>Abstract:</b> Modern nonlinear control theory seeks to develop feedback controllers that endow systems with properties such as safety and stability. The guarantees ensured by these controllers often rely on accurate estimates of the system state for determining control actions. In practice, measurement model uncertainty can lead to error in state estimates that degrades these guarantees. In this paper, we seek to unify techniques from control theory and machine learning to synthesize controllers that achieve safety in the presence of measurement model uncertainty. We define the notion of a Measurement-Robust Control Barrier Function (MR-CBF) as a tool for determining safe control inputs when facing measurement model uncertainty. Furthermore, MR-CBFs are used to inform sampling methodologies for learning-based perception systems and quantify tolerable error in the resulting learned models. We demonstrate the efficacy of MR-CBFs in achieving safety with measurement model uncertainty on a simulated Segway system.
    url: "assets/paper_materials/dean2020guaranteeing_safety_of_learned_perception_modules_via_measurement_robust_control_barrier_functions/paper.pdf"
    btn_label: "Paper"
    url2: "https://youtu.be/NE2KTAzU9qw"    
    btn_label2: "Presentation Video"
#    url3: "/assets/paper_materials/taylor2020adaptive_safety_with_control_barrier_functions/presentation_slides.pdf"
#    btn_label3: "Presentation Slides"

feature_row_2:
  - image_path: /assets/paper_materials/cosner2021measurement_robust_control_barrier_functions_certainty_in_safety_with_uncertainty_in_state/gait_tile.png
    title: "Measurement-Robust Control Barrier Functions: Certainty in Safety with Uncertainty in State"
    excerpt: Ryan K. Cosner, Andrew W. Singletary, <b>Andrew J. Taylor</b>, Tamas G. Molnár, Katherine L. Bouman, and Aaron D. Ames, in <i>Proceedings of the IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)</i>, Prague, Czech Republic, 2021, pp.6286-6291. <br> <br> <b>Abstract:</b> The increasing complexity of modern robotic systems and the environments they operate in necessitates the formal consideration of safety in the presence of imperfect measurements. In this paper we propose a rigorous framework for safety-critical control of systems with erroneous state estimates. We develop this framework by leveraging Control Barrier Functions (CBFs) and unifying the method of Backup Sets for synthesizing control invariant sets with robustness requirements---the end result is the synthesis of <i>Measurement-Robust Control Barrier Functions (MR-CBFs)</i>. This provides theoretical guarantees on safe behavior in the presence of imperfect measurements and improved robustness over standard CBF approaches. We demonstrate the efficacy of this framework both in simulation and experimentally on a Segway platform using an onboard stereo-vision camera for state estimation.
    url: "/assets/paper_materials/cosner2021measurement_robust_control_barrier_functions_certainty_in_safety_with_uncertainty_in_state/paper.pdf"
    btn_label: "Paper"
    url2: "https://youtu.be/aBuiZwaOBUk"
    btn_label2: "Supplemental Video"
---

{% include feature_row id = "intro" type = "center" %}

{% include feature_row id = "feature_row_2" type = "left" %}

{% include feature_row id = "feature_row_1" type = "left" %}
