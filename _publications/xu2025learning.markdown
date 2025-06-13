---
layout: publication
title: 'J4R: Learning To Judge With Equivalent Initial State Group Relative Policy Optimization'
authors: Austin Xu, Yilun Zhou, Xuan-phi Nguyen, Caiming Xiong, Shafiq Joty
conference: "Arxiv"
year: 2025
bibkey: xu2025learning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.13346"}
tags: ['Agentic', 'Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Reinforcement Learning', 'GPT', 'Ethics and Bias']
---
To keep pace with the increasing pace of large language models (LLM) development, model output evaluation has transitioned away from time-consuming human evaluation to automatic evaluation, where LLMs themselves are tasked with assessing and critiquing other model outputs. LLM-as-judge models are a class of generative evaluators that excel in evaluating relatively simple domains, like chat quality, but struggle in reasoning intensive domains where model responses contain more substantive and challenging content. To remedy existing judge shortcomings, we explore training judges with reinforcement learning (RL). We make three key contributions: (1) We propose the Equivalent Initial State Group Relative Policy Optimization (EIS-GRPO) algorithm, which allows us to train our judge to be robust to positional biases that arise in more complex evaluation settings. (2) We introduce ReasoningJudgeBench, a benchmark that evaluates judges in diverse reasoning settings not covered by prior work. (3) We train Judge for Reasoning (J4R), a 7B judge trained with EIS-GRPO that outperforms GPT-4o and the next best small judge by 6.7% and 9%, matching or exceeding the performance of larger GRPO-trained judges on both JudgeBench and ReasoningJudgeBench.
