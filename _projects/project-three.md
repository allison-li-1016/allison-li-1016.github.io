---
title: "Model prediction of SynNotch CAR T therapy successes and pitfalls"
summary: "Designing predictive SynNotch CAR T agent, analyzing parameter sweeps, forecasting therapy performance in immunosuppressive environments."
image: /assets/img/projects/project-three.png
links:
#   - label: "Paper"
#     url: "https://example.com"
#   - label: "Code"
#     url: "https://github.com/yourname/project-two"
---

CAR T therapies fail in solid tumors largely because of heterogeneous surface-antigen expression: **tumor-specific antigens that are highly expressed across all tumor cells are difficult to identify.** To address this, synthetic biologists have incorporated logic gates into antigen recognition to improve specificity. The SynNotch CAR T therapy applies an IF-THEN gate: on encountering a tumor-specific antigen, the T cell expresses receptors that target tumor-associated antigens.

This approach has proven successful *in vitro* and *in vivo*, but the circuit's design space and its robustness to challenging tumor microenvironment (TME) conditions remain unknown. We develop a spatiotemporal model of the SynNotch circuit to **(1) recapitulate known circuit behavior, (2) optimize therapeutic efficacy through parameter sweeps, and (3) predict circuit resilience to increasing immunosuppression.** The goal is to guide parameter tuning and identify potential design flaws.

In the model, individual cells act as autonomous agents whose states and actions follow defined rulesets, with subcellular processes described by ordinary differential equations (ODEs). Cells occupy a hexagonal grid that tracks their positions, and signaling molecules diffuse across it according to partial differential equations (PDEs). Circuit parameters are calibrated to dynamics reported in the literature.

This framework captures the multiscale dynamics of cell therapies, reproduces the spatial structure of the TME, and accommodates alternative genetic circuits, parameter sets, and therapeutic interventions to inform therapy design.
