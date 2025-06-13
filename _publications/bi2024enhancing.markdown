---
layout: publication
title: 'Enhancing The Reasoning Capabilities Of Small Language Models Via Solution Guidance Fine-tuning'
authors: Jing Bi, Yuting Wu, Weiwei Xing, Zhenjie Wei
conference: "Arxiv"
year: 2024
bibkey: bi2024enhancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.09906"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Pretraining Methods', 'Fine-Tuning', 'Prompting']
---
Large language models (LLMs) have demonstrated remarkable performance across
a wide range of tasks. Advances in prompt engineering and fine-tuning
techniques have further enhanced their ability to address complex reasoning
challenges. However, these advanced capabilities are often exclusive to models
exceeding 100 billion parameters. Although Chain-of-Thought (CoT) fine-tuning
methods have been explored for smaller models (under 10 billion parameters),
they typically depend on extensive CoT training data, which can introduce
inconsistencies and limit effectiveness in low-data settings. To overcome these
limitations, this paper introduce a new reasoning strategy Solution Guidance
(SG) and a plug-and-play training paradigm Solution-Guidance Fine-Tuning (SGFT)
for enhancing the reasoning capabilities of small language models. SG focuses
on problem understanding and decomposition at the semantic and logical levels,
rather than specific computations, which can effectively improve the SLMs'
generalization and reasoning abilities. With only a small amount of SG training
data, SGFT can fine-tune a SLM to produce accurate problem-solving guidances,
which can then be flexibly fed to any SLM as prompts, enabling it to generate
correct answers directly. Experimental results demonstrate that our method
significantly improves the performance of SLMs on various reasoning tasks,
enhancing both their practicality and efficiency within resource-constrained
environments.
