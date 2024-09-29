---
layout: publication
title: POP&#58; Prompt Of Prompts For Continual Learning
authors: Hu Zhiyuan, Lyu Jiancheng, Gao Dashan, Vasconcelos Nuno
conference: "Arxiv"
year: 2023
bibkey: hu2023prompt
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2306.08200"}
tags: ['Attention Mechanism', 'Few Shot', 'Model Architecture', 'Prompting', 'Reinforcement Learning', 'Training Techniques']
---
Continual learning (CL) has attracted increasing attention in the recent past. It aims to mimic the human ability to learn new concepts without catastrophic forgetting. While existing CL methods accomplish this to some extent they are still prone to semantic drift of the learned feature space. Foundation models which are endowed with a robust feature representation learned from very large datasets provide an interesting substrate for the solution of the CL problem. Recent work has also shown that they can be adapted to specific tasks by prompt tuning techniques that leave the generality of the representation mostly unscathed. An open question is however how to learn both prompts that are task specific and prompts that are global i.e. capture cross-task information. In this work we propose the Prompt Of Prompts (POP) model which addresses this goal by progressively learning a group of task-specified prompts and a group of global prompts denoted as POP to integrate information from the former. We show that a foundation model equipped with POP learning is able to outperform classic CL methods by a significant margin. Moreover as prompt tuning only requires a small set of training samples POP is able to perform CL in the few-shot setting while still outperforming competing methods trained on the entire dataset.
