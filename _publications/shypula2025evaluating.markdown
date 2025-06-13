---
layout: publication
title: 'Evaluating The Diversity And Quality Of LLM Generated Content'
authors: Alexander Shypula, Shuo Li, Botong Zhang, Vishakh Padmakumar, Kayo Yin, Osbert Bastani
conference: "Arxiv"
year: 2025
bibkey: shypula2025evaluating
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.12522'}
tags: ['Agentic', 'Applications', 'Tools', 'Scaling Laws', 'Fine-Tuning', 'Reinforcement Learning']
---
Recent work suggests that preference-tuning techniques--including
Reinforcement Learning from Human Preferences (RLHF) methods like PPO and GRPO,
as well as alternatives like DPO--reduce diversity, creating a dilemma given
that such models are widely deployed in applications requiring diverse outputs.
To address this, we introduce a framework for measuring effective semantic
diversity--diversity among outputs that meet quality thresholds--which better
reflects the practical utility of large language models (LLMs). Using
open-ended tasks that require no human intervention, we find counterintuitive
results: although preference-tuned models--especially those trained via
RL--exhibit reduced lexical and syntactic diversity, they produce greater
effective semantic diversity than SFT or base models, not from increasing
diversity among high-quality outputs, but from generating more high-quality
outputs overall. We discover that preference tuning reduces syntactic diversity
while preserving semantic diversity--revealing a distinction between diversity
in form and diversity in content that traditional metrics often overlook. Our
analysis further shows that smaller models are consistently more
parameter-efficient at generating unique content within a fixed sampling
budget, offering insights into the relationship between model scaling and
diversity. These findings have important implications for applications that
require diverse yet high-quality outputs, from creative assistance to synthetic
data generation.
