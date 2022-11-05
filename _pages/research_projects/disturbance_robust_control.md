---
title: Disturbance Robust Safety-Critical Control
layout: splash
classes: wide

intro:
  - title: "Disturbance Robust Safety-Critical Control"
    excerpt: TBD

feature_row_1:
  - image_path: assets/paper_materials/alan2021safe_controller_synthesis_with_tunable_input_to_state_safe_control_barrier_functions/issf_example.JPG
    title: "Safe Controller Synthesis with Tunable Input-to-State Safe Control Barrier Functions"
    excerpt: Anil Alan, <b>Andrew J. Taylor</b>, Chaozhe R. He, Gabor Orosz, and Aaron D. Ames, <i>IEEE Control Systems Letter</i>, vol. 6, pp. 908-913, 2021. <br> <br> <b>Abstract:</b> To bring complex systems into real world environments in a safe manner, they will have to be robust to uncertainties---both in the environment and the system.  This paper investigates the safety of control systems under input disturbances, wherein the disturbances can capture uncertainties in the system.  Safety, framed as forward invariance of sets in the state space, is ensured with the framework of control barrier functions (CBFs). Concretely, the definition of input-to-state safety (ISSf) is generalized to allow the synthesis of non-conservative, tunable controllers that are provably safe under varying disturbances. This is achieved by formulating the concept of tunable input-to-state safe control barrier functions (TISSf-CBFs), which guarantee safety for disturbances that vary with state and, therefore, provide less conservative means of accommodating uncertainty. The theoretical results are demonstrated with a simple control system with input disturbance and also applied to design a safe connected cruise controller for a heavy duty truck.
    url: "assets/paper_materials/alan2021safe_controller_synthesis_with_tunable_input_to_state_safe_control_barrier_functions/paper.pdf"
    btn_label: "Paper"


feature_row_2:
  - image_path: assets/images/truck.png
    title: "Control Barrier Functions and Input-to-State Safety with Application to Automated Vehicles"
    excerpt: Anil Alan, <b> Andrew J. Taylor </b>, Chaozhe R. He, Aaron D. Ames, and Gabor Orosz, submitted to <i>IEEE Transactions on Control Systems Technology (TCST)</i>, 2022. <br> <br> <b>Abstract:</b> Balancing safety and performance is one of the predominant challenges in modern control system design. Moreover, it is crucial to robustly ensure safety without inducing unnecessary conservativeness that degrades performance. In this work we present a constructive approach for safety-critical control synthesis via <i>Control Barrier Functions</i> (CBF). By filtering a hand-designed controller via a CBF, we are able to attain performant behavior while providing rigorous guarantees of safety. In the face of disturbances, robust safety and performance are simultaneously achieved through the notion of <i>Input-to-State Safety</i> (ISSf). We take a tutorial approach by developing the CBF-design methodology in parallel with an inverted pendulum example, making the challenges and sensitivities in the design process concrete. To establish the capability of the proposed approach, we consider the practical setting of safety-critical design via CBFs for a <i>connected automated vehicle</i> (CAV) in the form of a class-8 truck without a trailer. Through experimentation we see the impact of unmodeled disturbances in the truck's actuation system on the safety guarantees provided by CBFs. We characterize these disturbances and using ISSf, produce a robust controller that achieves safety without conceding performance. We evaluate our design both in simulation, and for the first time on an automotive system, experimentally.
    url: "assets/paper_materials/alan2022control_barrier_functions_and_input_to_state_safety_with_application_to_automated_vehicles/preprint.pdf"
    btn_label: "Preprint"
---

{% include feature_row id = "intro" type = "center" %}

{% include feature_row id = "feature_row_2" type = "left" %}

{% include feature_row id = "feature_row_1" type = "left" %}
