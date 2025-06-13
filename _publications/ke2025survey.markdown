---
layout: publication
title: 'A Survey Of Frontiers In LLM Reasoning: Inference Scaling, Learning To Reason, And Agentic Systems'
authors: Zixuan Ke, Fangkai Jiao, Yifei Ming, Xuan-phi Nguyen, Austin Xu, Do Xuan Long, Minzhi Li, Chengwei Qin, Peifeng Wang, Silvio Savarese, Caiming Xiong, Shafiq Joty
conference: "Arxiv"
year: 2025
bibkey: ke2025survey
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.09037"}
tags: ['Agentic', 'Training Techniques', 'Model Architecture', 'Survey Paper', 'Tools', 'Reinforcement Learning', 'Merging', 'Pretraining Methods', 'Fine-Tuning', 'Prompting']
---
Reasoning is a fundamental cognitive process that enables logical inference,
problem-solving, and decision-making. With the rapid advancement of large
language models (LLMs), reasoning has emerged as a key capability that
distinguishes advanced AI systems from conventional models that empower
chatbots. In this survey, we categorize existing methods along two orthogonal
dimensions: (1) Regimes, which define the stage at which reasoning is achieved
(either at inference time or through dedicated training); and (2)
Architectures, which determine the components involved in the reasoning
process, distinguishing between standalone LLMs and agentic compound systems
that incorporate external tools, and multi-agent collaborations. Within each
dimension, we analyze two key perspectives: (1) Input level, which focuses on
techniques that construct high-quality prompts that the LLM condition on; and
(2) Output level, which methods that refine multiple sampled candidates to
enhance reasoning quality. This categorization provides a systematic
understanding of the evolving landscape of LLM reasoning, highlighting emerging
trends such as the shift from inference-scaling to learning-to-reason (e.g.,
DeepSeek-R1), and the transition to agentic workflows (e.g., OpenAI Deep
Research, Manus Agent). Additionally, we cover a broad spectrum of learning
algorithms, from supervised fine-tuning to reinforcement learning such as PPO
and GRPO, and the training of reasoners and verifiers. We also examine key
designs of agentic workflows, from established patterns like
generator-evaluator and LLM debate to recent innovations. ...
