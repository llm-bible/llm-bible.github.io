---
layout: publication
title: 'PIM-AI: A Novel Architecture For High-efficiency LLM Inference'
authors: Cristobal Ortega, Yann Falevoz, Renaud Ayrignac
conference: "Arxiv"
year: 2024
bibkey: ortega2024pim
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.17309"}
tags: ['Efficiency and Optimization', 'Model Architecture', 'Applications']
---
Large Language Models (LLMs) have become essential in a variety of
applications due to their advanced language understanding and generation
capabilities. However, their computational and memory requirements pose
significant challenges to traditional hardware architectures.
Processing-in-Memory (PIM), which integrates computational units directly into
memory chips, offers several advantages for LLM inference, including reduced
data transfer bottlenecks and improved power efficiency.
  This paper introduces PIM-AI, a novel DDR5/LPDDR5 PIM architecture designed
for LLM inference without modifying the memory controller or DDR/LPDDR memory
PHY. We have developed a simulator to evaluate the performance of PIM-AI in
various scenarios and demonstrate its significant advantages over conventional
architectures. In cloud-based scenarios, PIM-AI reduces the 3-year TCO per
queries-per-second by up to 6.94x compared to state-of-the-art GPUs, depending
on the LLM model used. In mobile scenarios, PIM-AI achieves a 10- to 20-fold
reduction in energy per token compared to state-of-the-art mobile SoCs,
resulting in 25 to 45~% more queries per second and 6.9x to 13.4x less energy
per query, extending battery life and enabling more inferences per charge.
These results highlight PIM-AI's potential to revolutionize LLM deployments,
making them more efficient, scalable, and sustainable.
