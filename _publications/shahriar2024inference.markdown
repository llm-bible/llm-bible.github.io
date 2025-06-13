---
layout: publication
title: 'Inference Time LLM Alignment In Single And Multidomain Preference Spectrum'
authors: Sadat Shahriar, Zheng Qi, Nikolaos Pappas, Srikanth Doss, Monica Sunkara, Kishaloy Halder, Manuel Mager, Yassine Benajiba
conference: "Arxiv"
year: 2024
bibkey: shahriar2024inference
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.19206'}
tags: ['Training Techniques', 'Fine-Tuning', 'Prompting', 'Reinforcement Learning', 'Pretraining Methods']
---
Aligning Large Language Models (LLM) to address subjectivity and nuanced
preference levels requires adequate flexibility and control, which can be a
resource-intensive and time-consuming procedure. Existing training-time
alignment methods require full re-training when a change is needed and
inference-time ones typically require access to the reward model at each
inference step. To address these limitations, we introduce inference-time model
alignment method that learns encoded representations of preference dimensions,
called \textit\{Alignment Vectors\} (AV). These representations are computed by
subtraction of the base model from the aligned model as in model editing
enabling dynamically adjusting the model behavior during inference through
simple linear operations. Even though the preference dimensions can span
various granularity levels, here we focus on three gradual response levels
across three specialized domains: medical, legal, and financial, exemplifying
its practical potential. This new alignment paradigm introduces adjustable
preference knobs during inference, allowing users to tailor their LLM outputs
while reducing the inference cost by half compared to the prompt engineering
approach. Additionally, we find that AVs are transferable across different
fine-tuning stages of the same model, demonstrating their flexibility. AVs also
facilitate multidomain, diverse preference alignment, making the process 12x
faster than the retraining approach.
