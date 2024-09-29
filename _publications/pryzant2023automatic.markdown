---
layout: publication
title: Automatic Prompt Optimization with Gradient Descent and Beam Search
authors: Pryzant Reid, Iter Dan, Li Jerry, Lee Yin Tat, Zhu Chenguang, Zeng Michael
conference: "Arxiv"
year: 2023
bibkey: pryzant2023automatic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.03495"}
tags: ['Agentic', 'Efficiency And Optimization', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Large Language Models (LLMs) have shown impressive performance as general purpose agents but their abilities remain highly dependent on prompts which are hand written with onerous trial-and-error effort. We propose a simple and nonparametric solution to this problem Automatic Prompt Optimization (APO) which is inspired by numerical gradient descent to automatically improve prompts assuming access to training data and an LLM API. The algorithm uses minibatches of data to form natural language gradients that criticize the current prompt. The gradients are then propagated into the prompt by editing the prompt in the opposite semantic direction of the gradient. These gradient descent steps are guided by a beam search and bandit selection procedure which significantly improves algorithmic efficiency. Preliminary results across three benchmark NLP tasks and the novel problem of LLM jailbreak detection suggest that Automatic Prompt Optimization can outperform prior prompt editing techniques and improve an initial prompts performance by up to 31 by using data to rewrite vague task descriptions into more precise annotation instructions.
