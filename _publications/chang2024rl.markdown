---
layout: publication
title: 'Rl-star: Theoretical Analysis Of Reinforcement Learning Frameworks For Self-taught Reasoner'
authors: Fu-chieh Chang, Yu-ting Lee, Hui-ying Shih, Yi Hsuan Tseng, Pei-yuan Wu
conference: "ICLR 2025 Workshop on Reasoning and Planning for Large Language Models"
year: 2024
bibkey: chang2024rl
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.23912'}
tags: ['Agentic', 'Security', 'Training Techniques', 'Tools', 'Prompting', 'Reinforcement Learning']
---
The reasoning abilities of large language models (LLMs) have improved with
chain-of-thought (CoT) prompting, allowing models to solve complex tasks
stepwise. However, training CoT capabilities requires detailed reasoning data,
which is often scarce. The self-taught reasoner (STaR) framework addresses this
by using reinforcement learning to automatically generate reasoning steps,
reducing reliance on human-labeled data. Although STaR and its variants have
demonstrated empirical success, a theoretical foundation explaining these
improvements is lacking. This work provides a theoretical framework for
understanding the effectiveness of reinforcement learning on CoT reasoning and
STaR. Our contributions are: (1) criteria for the quality of pre-trained models
necessary to initiate effective reasoning improvement; (2) an analysis of
policy improvement, showing why LLM reasoning improves iteratively with STaR;
(3) conditions for convergence to an optimal reasoning policy; and (4) an
examination of STaR's robustness, explaining how it can improve reasoning even
when incorporating occasional incorrect steps; This framework aims to bridge
empirical findings with theoretical insights, advancing reinforcement learning
approaches for reasoning in LLMs.
