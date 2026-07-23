---
title: "Spatiotemporal modeling of inhibitory CAR T therapies in the tumor microenvironment"
summary: "Identifying iCAR therapy successes and shortcomings in different spatial contexts, proposing and testing strategies to improve therapeutic outcomes."
image: /assets/img/projects/project-one.png
links:
  # - label: "Paper"
  #   url: "https://example.com"
  # - label: "Code"
  #   url: "https://github.com/bagherilab/ARCADE"
---

CAR T cell therapies have transformed the treatment of hematological cancers, with several now approved by the FDA. This success has not extended to solid tumors, which present additional obstacles, one of them being heterogeneous surface-antigen expression. **Effective targeting requires antigens that are both unique to cancer cells and uniformly expressed across them, and such antigens are rare.** To address this limitation, synthetic biologists have incorporated logic gates into antigen recognition to improve targeting specificity. The inhibitory CAR (iCAR) applies a NOT gate: it recognizes cancer antigens while discriminating against healthy tissue that expresses the inhibitory antigen.

A principal limitation of iCARs is early off-target cytotoxicity, which results from a delay in the onset of inhibition. We develop a spatiotemporal model of the iCAR circuit in order to **(1) evaluate strategies for reducing this inhibition delay, and (2) predict iCAR efficacy across a range of tumor microenvironment (TME) conditions.**

In this model, individual cells act as autonomous agents whose states and actions are governed by defined rulesets, with subcellular processes described by ordinary differential equations (ODEs). Cells occupy a hexagonal grid that tracks their positions, and signaling molecules diffuse across the grid according to partial differential equations (PDEs).

This framework enables us to capture the multiscale dynamics of cell therapies, reproduce the spatial structure of the TME, and incorporate alternative genetic circuits, parameter sets, and therapeutic interventions to inform therapy design.


