---
layout: publication
title: Inferaligner Inference45;time Alignment For Harmlessness Through Cross45;model Guidance
authors: Wang Pengyu, Zhang Dong, Li Linyang, Tan Chenkun, Wang Xinghao, Ren Ke, Jiang Botian, Qiu Xipeng
conference: "Arxiv"
year: 2024
bibkey: wang2024inference
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.11206"}
tags: ['Agentic', 'Applications', 'Fine Tuning', 'Multimodal Models', 'Reinforcement Learning', 'Responsible AI', 'Security', 'Tools', 'Training Techniques']
---
With the rapid development of large language models (LLMs) they are not only used as general45;purpose AI assistants but are also customized through further fine45;tuning to meet the requirements of different applications. A pivotal factor in the success of current LLMs is the alignment process. Current alignment methods such as supervised fine45;tuning (SFT) and reinforcement learning from human feedback (RLHF) focus on training45;time alignment and are often complex and cumbersome to implement. Therefore we develop textbf123;InferAligner125; a novel inference45;time alignment method that utilizes cross45;model guidance for harmlessness alignment. InferAligner utilizes safety steering vectors extracted from safety45;aligned model to modify the activations of the target model when responding to harmful inputs thereby guiding the target model to provide harmless responses. Experimental results show that our method can be very effectively applied to domain45;specific models in finance medicine and mathematics as well as to multimodal large language models (MLLMs) such as LLaVA. It significantly diminishes the Attack Success Rate (ASR) of both harmful instructions and jailbreak attacks while maintaining almost unchanged performance in downstream tasks.
