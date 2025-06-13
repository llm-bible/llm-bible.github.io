---
layout: publication
title: 'Drift: Decoding-time Personalized Alignments With Implicit User Preferences'
authors: Minbeom Kim, Kang-il Lee, Seongho Joo, Hwaran Lee, Thibaut Thonet, Kyomin Jung
conference: "Arxiv"
year: 2025
bibkey: kim2025decoding
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.14289"}
tags: ['Agentic', 'Training Techniques', 'Tools', 'Reinforcement Learning']
---
Personalized alignments for individual users have been a long-standing goal
in large language models (LLMs). We introduce Drift, a novel framework that
personalizes LLMs at decoding time with implicit user preferences. Traditional
Reinforcement Learning from Human Feedback (RLHF) requires thousands of
annotated examples and expensive gradient updates. In contrast, Drift
personalizes LLMs in a training-free manner, using only a few dozen examples to
steer a frozen model through efficient preference modeling. Our approach models
user preferences as a composition of predefined, interpretable attributes and
aligns them at decoding time to enable personalized generation. Experiments on
both a synthetic persona dataset (Perspective) and a real human-annotated
dataset (PRISM) demonstrate that Drift significantly outperforms RLHF baselines
while using only 50-100 examples. Our results and analysis show that Drift is
both computationally efficient and interpretable.
