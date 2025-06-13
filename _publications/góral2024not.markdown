---
layout: publication
title: 'Wait, That''s Not An Option: Llms Robustness With Incorrect Multiple-choice Options'
authors: Gracjan Góral, Emilia Wiśnios, Piotr Sankowski, Paweł Budzianowski
conference: "Arxiv"
year: 2024
bibkey: góral2024not
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.00113"}
tags: ['Security', 'Training Techniques', 'Efficiency and Optimization', 'Tools', 'Reinforcement Learning', 'Ethics and Bias', 'Prompting']
---
This work introduces a novel framework for evaluating LLMs' capacity to balance instruction-following with critical reasoning when presented with multiple-choice questions containing no valid answers. Through systematic evaluation across arithmetic, domain-specific knowledge, and high-stakes medical decision tasks, we demonstrate that post-training aligned models often default to selecting invalid options, while base models exhibit improved refusal capabilities that scale with model size. Our analysis reveals that alignment techniques, though intended to enhance helpfulness, can inadvertently impair models' reflective judgment--the ability to override default behaviors when faced with invalid options. We additionally conduct a parallel human study showing similar instruction-following biases, with implications for how these biases may propagate through human feedback datasets used in alignment. We provide extensive ablation studies examining the impact of model size, training techniques, and prompt engineering. Our findings highlight fundamental tensions between alignment optimization and preservation of critical reasoning capabilities, with important implications for developing more robust AI systems for real-world deployment.
