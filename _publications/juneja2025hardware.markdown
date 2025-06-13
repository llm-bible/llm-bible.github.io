---
layout: publication
title: 'HALO: Hardware-aware Quantization With Low Critical-path-delay Weights For LLM Acceleration'
authors: Rohan Juneja, Shivam Aggarwal, Safeen Huda, Tulika Mitra, Li-shiuan Peh
conference: "Arxiv"
year: 2025
bibkey: juneja2025hardware
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.19662"}
tags: ['Tools', 'Efficiency and Optimization', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Quantization']
---
Quantization is critical for efficiently deploying large language models
(LLMs). Yet conventional methods remain hardware-agnostic, limited to bit-width
constraints, and do not account for intrinsic circuit characteristics such as
the timing behaviors and energy profiles of Multiply-Accumulate (MAC) units.
This disconnect from circuit-level behavior limits the ability to exploit
available timing margins and energy-saving opportunities, reducing the overall
efficiency of deployment on modern accelerators.
  To address these limitations, we propose HALO, a versatile framework for
Hardware-Aware Post-Training Quantization (PTQ). Unlike traditional methods,
HALO explicitly incorporates detailed hardware characteristics, including
critical-path timing and power consumption, into its quantization approach.
HALO strategically selects weights with low critical-path-delays enabling
higher operational frequencies and dynamic frequency scaling without disrupting
the architecture's dataflow. Remarkably, HALO achieves these improvements with
only a few dynamic voltage and frequency scaling (DVFS) adjustments, ensuring
simplicity and practicality in deployment. Additionally, by reducing switching
activity within the MAC units, HALO effectively lowers energy consumption.
Evaluations on accelerators such as Tensor Processing Units (TPUs) and Graphics
Processing Units (GPUs) demonstrate that HALO significantly enhances inference
efficiency, achieving average performance improvements of 270% and energy
savings of 51% over baseline quantization methods, all with minimal impact on
accuracy.
