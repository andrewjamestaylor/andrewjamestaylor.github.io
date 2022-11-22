---
title: Safety-Critical Control for Higher-Order Systems
layout: splash
classes: wide

intro:
  - title: "Safety-Critical Control for Higher-Order Systems"
    excerpt: "Constructing rigorous control system designs for high-dimensional,
              complex nonlinear systems can be exceptionally difficult. Classical
              tools from nonlinear control theory such as backstepping provide a
              constructive framework for designing controllers using simplified
              models that yield designs for full-order models. My work focuses
              on extending these tools to the safety-critical control setting."

feature_row_1:
  - image_path: assets/images/backstepping_unicycle_avoid.png
    title: "Safe Backstepping with Control Barrier Functions"
    excerpt: <b>Andrew J. Taylor</b>, Pio Ong, Tamas G. Molnár, and Aaron D. Ames, in <i>Proceedings of the IEEE 61st Conference on Decision and Control (CDC)</i>, Cancún, Mexico, 2022. <br> <br> <b>Abstract:</b> Complex control systems are often described in a layered fashion, represented as <i>higher-order systems</i> where the inputs appear after a chain of integrators. While Control Barrier Functions (CBFs) have proven to be powerful tools for safety-critical controller design of nonlinear systems, their application to higher-order systems adds complexity to the controller synthesis process---it necessitates dynamically extending the CBF to include higher order terms, which consequently modifies the safe set in complex ways. We propose an alternative approach for addressing safety of higher-order systems through <i>Control Barrier Function Backstepping</i>. Drawing inspiration from the method of Lyapunov backstepping, we provide a constructive framework for synthesizing safety-critical controllers and CBFs for higher-order systems from a top-level dynamics safety specification and controller design. Furthermore, we integrate the proposed method with Lyapunov backstepping, allowing the tasks of stability and safety to be expressed individually but achieved jointly. We demonstrate the efficacy of this approach in simulation.
    url: "assets/paper_materials/taylor2022safe_backstepping_with_control_barrier_functions/paper.pdf"
    btn_label: "Paper"
    url2: "https://youtu.be/B4YWzL8-6gE"
    btn_label2: "Presentation Video"
    url3: "assets/paper_materials/taylor2022safe_backstepping_with_control_barrier_functions/presentation_slides.pdf"
    btn_label3: "Presentation Slides"
---

{% include feature_row id = "intro" type = "center" %}

{% include feature_row id = "feature_row_1" type = "left" %}
