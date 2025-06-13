---
layout: publication
title: 'Diversified Sampling Improves Scaling LLM Inference'
authors: Tianchun Wang, Zichuan Liu, Yuanzhou Chen, Jonathan Light, Haifeng Chen, Xiang Zhang, Wei Cheng
conference: "Arxiv"
year: 2025
bibkey: wang2025diversified
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.11027"}
tags: ['Prompting', 'Training Techniques', 'Applications']
---
While increasing training compute has significantly improved the performance
of large language models (LLMs), similar gains have not been observed when
scaling inference compute. We hypothesize that the primary issue lies in the
uniformity of LLM outputs, which leads to inefficient sampling as models
repeatedly generate similar but inaccurate responses. Motivated by an
intriguing relationship between solution accuracy (Pass@10) and response
diversity, we propose DivSampling -- a novel and versatile sampling technique
designed to enhance the diversity of candidate solutions by introducing prompt
perturbations.DivSampling incorporates two categories of perturbations:
task-agnostic approaches, which are general and not tailored to any specific
task, and task-specific approaches, which are customized based on task content.
Our theoretical analysis demonstrates that, under mild assumptions, the error
rates of responses generated from diverse prompts are significantly lower
compared to those produced by stationary prompts. Comprehensive evaluations
across various tasks -- including reasoning, mathematics, and code generation
-- highlight the effectiveness of DivSampling in improving solution accuracy.
This scalable and efficient approach offers a new perspective on optimizing
test-time inference, addressing limitations in current sampling strategies.
