---
layout: publication
title: Hybrid Preference Optimization Augmenting Direct Preference Optimization With Auxiliary Objectives
authors: Badrinath Anirudhan, Agarwal Prabhat, Xu Jiajing
conference: "Arxiv"
year: 2024
bibkey: badrinath2024hybrid
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.17956"}
tags: ['Agentic', 'Efficiency And Optimization', 'RAG', 'Reinforcement Learning', 'Tools']
---
For aligning large language models (LLMs) prior work has leveraged reinforcement learning via human feedback (RLHF) or variations of direct preference optimization (DPO). While DPO offers a simpler framework based on maximum likelihood estimation it compromises on the ability to tune language models to easily maximize non-differentiable and non-binary objectives according to the LLM designers preferences (e.g. using simpler language or minimizing specific kinds of harmful content). These may neither align with user preferences nor even be able to be captured tractably by binary preference data. To leverage the simplicity and performance of DPO with the generalizability of RL we propose a hybrid approach between DPO and RLHF. With a simple augmentation to the implicit reward decomposition of DPO we allow for tuning LLMs to maximize a set of arbitrary auxiliary rewards using offline RL. The proposed method Hybrid Preference Optimization (HPO) shows the ability to effectively generalize to both user preferences and auxiliary designer objectives while preserving alignment performance across a range of challenging benchmarks and model sizes.
