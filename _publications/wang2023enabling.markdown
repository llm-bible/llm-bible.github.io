---
layout: publication
title: 'Enabling Language Models To Implicitly Learn Self-improvement'
authors: Ziqi Wang, Le Hou, Tianjian Lu, Yuexin Wu, Yunxuan Li, Hongkun Yu, Heng Ji
conference: "Arxiv"
year: 2023
bibkey: wang2023enabling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.00898"}
tags: ['Agentic', 'Efficiency and Optimization', 'Tools', 'Applications', 'Language Modeling', 'Reinforcement Learning', 'Training Techniques', 'Prompting']
---
Large Language Models (LLMs) have demonstrated remarkable capabilities in
open-ended text generation tasks. However, the inherent open-ended nature of
these tasks implies that there is always room for improvement in the quality of
model responses. To address this challenge, various approaches have been
proposed to enhance the performance of LLMs. There has been a growing focus on
enabling LLMs to self-improve their response quality, thereby reducing the
reliance on extensive human annotation efforts for collecting diverse and
high-quality training data. Recently, prompting-based methods have been widely
explored among self-improvement methods owing to their effectiveness,
efficiency, and convenience. However, those methods usually require explicitly
and thoroughly written rubrics as inputs to LLMs. It is expensive and
challenging to manually derive and provide all necessary rubrics with a
real-world complex goal for improvement (e.g., being more helpful and less
harmful). To this end, we propose an ImPlicit Self-ImprovemenT (PIT) framework
that implicitly learns the improvement goal from human preference data. PIT
only requires preference data that are used to train reward models without
extra human efforts. Specifically, we reformulate the training objective of
reinforcement learning from human feedback (RLHF) -- instead of maximizing
response quality for a given input, we maximize the quality gap of the response
conditioned on a reference response. In this way, PIT is implicitly trained
with the improvement goal of better aligning with human preferences.
Experiments on two real-world datasets and one synthetic dataset show that our
method significantly outperforms prompting-based methods.
