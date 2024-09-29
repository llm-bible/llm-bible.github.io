---
layout: publication
title: Distilling Instruction45;following Abilities Of Large Language Models With Task45;aware Curriculum Planning
authors: Yue Yuanhao, Wang Chengyu, Huang Jun, Wang Peng
conference: "Arxiv"
year: 2024
bibkey: yue2024distilling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.13448"}
tags: ['Applications', 'Distillation', 'Efficiency And Optimization', 'GPT', 'Model Architecture', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
The process of instruction tuning aligns pre45;trained large language models (LLMs) with open45;domain instructions and human45;preferred responses. While several studies have explored autonomous approaches to distilling and annotating instructions from more powerful proprietary LLMs such as ChatGPT they often neglect the impact of task distributions and the varying difficulty of instructions of the training sets. This oversight can lead to imbalanced knowledge capabilities and poor generalization powers of small student LLMs. To address this challenge we introduce Task45;Aware Curriculum Planning for Instruction Refinement (TAPIR) a multi45;round distillation framework with balanced task distributions and dynamic difficulty adjustment. This approach utilizes an oracle LLM to select instructions that are difficult for a student LLM to follow and distill instructions with balanced task distributions. By incorporating curriculum planning our approach systematically escalates the difficulty levels progressively enhancing the student LLMs capabilities. We rigorously evaluate TAPIR using two widely recognized benchmarks including AlpacaEval 2.0 and MT45;Bench. The empirical results demonstrate that the student LLMs trained with our method and less training data outperform larger instruction45;tuned models and strong distillation baselines. The improvement is particularly notable in complex tasks such as logical reasoning and code generation.
