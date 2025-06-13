---
layout: publication
title: 'Multi-view Intent Learning And Alignment With Large Language Models For Session-based Recommendation'
authors: Shutong Qiao, Wei Zhou, Junhao Wen, Chen Gao, Qun Luo, Peixuan Chen, Yong Li
conference: "Arxiv"
year: 2024
bibkey: qiao2024multi
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.13840"}
  - {name: "Code", url: "https://github.com/tsinghua-fib-lab/LLM4SBR"}
tags: ['Training Techniques', 'Tools', 'Reinforcement Learning', 'RAG', 'Merging', 'Has Code', 'Prompting']
---
Session-based recommendation (SBR) methods often rely on user behavior data,
which can struggle with the sparsity of session data, limiting performance.
Researchers have identified that beyond behavioral signals, rich semantic
information in item descriptions is crucial for capturing hidden user intent.
While large language models (LLMs) offer new ways to leverage this semantic
data, the challenges of session anonymity, short-sequence nature, and high LLM
training costs have hindered the development of a lightweight, efficient LLM
framework for SBR.
  To address the above challenges, we propose an LLM-enhanced SBR framework
that integrates semantic and behavioral signals from multiple views. This
two-stage framework leverages the strengths of both LLMs and traditional SBR
models while minimizing training costs. In the first stage, we use multi-view
prompts to infer latent user intentions at the session semantic level,
supported by an intent localization module to alleviate LLM hallucinations. In
the second stage, we align and unify these semantic inferences with behavioral
representations, effectively merging insights from both large and small models.
Extensive experiments on two real datasets demonstrate that the LLM4SBR
framework can effectively improve model performance. We release our codes along
with the baselines at https://github.com/tsinghua-fib-lab/LLM4SBR.
