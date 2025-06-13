---
layout: publication
title: 'Capturing Nuanced Preferences: Preference-aligned Distillation For Small Language Models'
authors: Yanggan Gu, Junzhuo Li, Sirui Huang, Xin Zou, Zhenghua Li, Xuming Hu
conference: "Arxiv"
year: 2025
bibkey: gu2025capturing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.14272"}
tags: ['Tools', 'Efficiency and Optimization', 'Reinforcement Learning', 'Training Techniques', 'Distillation']
---
Aligning small language models (SLMs) with human values typically involves
distilling preference knowledge from large language models (LLMs). However,
existing distillation methods model preference knowledge in teacher LLMs by
comparing pairwise responses, overlooking the extent of difference between
responses. This limitation hinders student SLMs from capturing the nuanced
preferences for multiple responses. In this paper, we propose a
Preference-Aligned Distillation (PAD) framework, which models teacher's
preference knowledge as a probability distribution over all potential
preferences, thereby providing more nuanced supervisory signals. Our insight in
developing PAD is rooted in the demonstration that language models can serve as
reward functions, reflecting their intrinsic preferences. Based on this, PAD
comprises three key steps: (1) sampling diverse responses using
high-temperature; (2) computing rewards for both teacher and student to
construct their intrinsic preference; and (3) training the student's intrinsic
preference distribution to align with the teacher's. Experiments on four
mainstream alignment benchmarks demonstrate that PAD consistently and
significantly outperforms existing approaches, achieving over 20% improvement
on AlpacaEval 2 and Arena-Hard, indicating superior alignment with human
preferences. Notably, on MT-Bench, using the \textsc\{Gemma\} model family, the
student trained by PAD surpasses its teacher, further validating the
effectiveness of our PAD.
