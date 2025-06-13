---
layout: publication
title: 'Z1: Efficient Test-time Scaling With Code'
authors: Zhaojian Yu, Yinghao Wu, Yilun Zhao, Arman Cohan, Xiao-ping Zhang
conference: "Arxiv"
year: 2025
bibkey: yu2025efficient
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.00810'}
tags: ['RAG']
---
Large Language Models (LLMs) can achieve enhanced complex problem-solving
through test-time computing scaling, yet this often entails longer contexts and
numerous reasoning token costs. In this paper, we propose an efficient
test-time scaling method that trains LLMs on code-related reasoning
trajectories, facilitating their reduction of excess thinking tokens while
maintaining performance. First, we create Z1-Code-Reasoning-107K, a curated
dataset of simple and complex coding problems paired with their short and long
solution trajectories. Second, we present a novel Shifted Thinking Window to
mitigate overthinking overhead by removing context-delimiting tags (e.g.,
<think>. . . </think>) and capping reasoning tokens. Trained with long and
short trajectory data and equipped with Shifted Thinking Window, our model,
Z1-7B, demonstrates the ability to adjust its reasoning level as the complexity
of problems and exhibits efficient test-time scaling across different reasoning
tasks that matches R1-Distill-Qwen-7B performance with about 30% of its average
thinking tokens. Notably, fine-tuned with only code trajectories, Z1-7B
demonstrates generalization to broader reasoning tasks (47.5% on GPQA Diamond).
Our analysis of efficient reasoning elicitation also provides valuable insights
for future research.
