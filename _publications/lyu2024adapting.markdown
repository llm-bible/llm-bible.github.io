---
layout: publication
title: 'Adapting While Learning: Grounding Llms For Scientific Problems With Intelligent Tool Usage Adaptation'
authors: Bohan Lyu, Yadi Cao, Duncan Watson-parris, Leon Bergen, Taylor Berg-kirkpatrick, Rose Yu
conference: "Arxiv"
year: 2024
bibkey: lyu2024adapting
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2411.00412'}
tags: ['GPT', 'Tools', 'Training Techniques', 'Fine-Tuning', 'Model Architecture', 'Reinforcement Learning', 'Pretraining Methods']
---
Large Language Models (LLMs) demonstrate promising capabilities in solving
simple scientific problems but, even with domain-specific fine-tuning, often
produce hallucinations for complex ones. While integrating LLMs with tools can
mitigate this reliability issue, models finetuned on tool usage only often
over-rely on them, incurring unnecessary costs from resource-intensive
scientific tools even for simpler problems. Inspired by how human experts
assess the complexity of the problem before choosing the solutions, we propose
a novel two-component fine-tuning method, Adapting While Learning (AWL). In the
first component, World Knowledge Learning (WKL), LLMs internalize scientific
knowledge by learning from tools-generated solutions. In the second component,
Tool Usage Adaptation (TUA), we classify questions as easy or hard based on the
WKL-trained model's accuracy, and train it to maintain direct reasoning for
simple problems while switching to tools for challenging ones. We validate our
method on 6 scientific benchmark datasets in climate science, epidemiology, and
mathematics. Compared to the base 8B model, our trained models achieve 28.27%
higher answer accuracy and 13.76% better tool usage accuracy, even surpassing
state-of-the-art models including GPT-4 and Claude-3.5 on 4 custom-created
datasets.
