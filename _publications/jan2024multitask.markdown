---
layout: publication
title: 'Multitask Mayhem: Unveiling And Mitigating Safety Gaps In Llms Fine-tuning'
authors: Essa Jan, Nouar Aldahoul, Moiz Ali, Faizan Ahmad, Fareed Zaffar, Yasir Zaki
conference: "Arxiv"
year: 2024
bibkey: jan2024multitask
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.15361"}
tags: ['Fine-Tuning', 'Responsible AI', 'Applications', 'Security', 'Training Techniques', 'Pretraining Methods', 'Prompting']
---
Recent breakthroughs in Large Language Models (LLMs) have led to their
adoption across a wide range of tasks, ranging from code generation to machine
translation and sentiment analysis, etc. Red teaming/Safety alignment efforts
show that fine-tuning models on benign (non-harmful) data could compromise
safety. However, it remains unclear to what extent this phenomenon is
influenced by different variables, including fine-tuning task, model
calibrations, etc. This paper explores the task-wise safety degradation due to
fine-tuning on downstream tasks such as summarization, code generation,
translation, and classification across various calibration. Our results reveal
that: 1) Fine-tuning LLMs for code generation and translation leads to the
highest degradation in safety guardrails. 2) LLMs generally have weaker
guardrails for translation and classification, with 73-92% of harmful prompts
answered, across baseline and other calibrations, falling into one of two
concern categories. 3) Current solutions, including guards and safety tuning
datasets, lack cross-task robustness. To address these issues, we developed a
new multitask safety dataset effectively reducing attack success rates across a
range of tasks without compromising the model's overall helpfulness. Our work
underscores the need for generalized alignment measures to ensure safer and
more robust models.
