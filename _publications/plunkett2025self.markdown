---
layout: publication
title: 'Self-interpretability: Llms Can Describe Complex Internal Processes That Drive Their Decisions, And Improve With Training'
authors: Dillon Plunkett, Adam Morris, Keerthi Reddy, Jorge Morales
conference: "Arxiv"
year: 2025
bibkey: plunkett2025self
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.17120'}
tags: ['Interpretability and Explainability', 'Training Techniques', 'Model Architecture', 'GPT', 'Fine-Tuning', 'Responsible AI', 'Pretraining Methods']
---
We have only limited understanding of how and why large language models (LLMs) respond in the ways that they do. Their neural networks have proven challenging to interpret, and we are only beginning to tease out the function of individual neurons and circuits within them. However, another path to understanding these systems is to investigate and develop their capacity to introspect and explain their own functioning. Here, we show that i) contemporary LLMs are capable of providing accurate, quantitative descriptions of their own internal processes during certain kinds of decision-making, ii) that it is possible to improve these capabilities through training, and iii) that this training generalizes to at least some degree. To do so, we fine-tuned GPT-4o and GPT-4o-mini to make decisions in a wide variety of complex contexts (e.g., choosing between condos, loans, vacations, etc.) according to randomly-generated, quantitative preferences about how to weigh different attributes during decision-making (e.g., the relative importance of natural light versus quiet surroundings for condos). We demonstrate that the LLMs can accurately report these preferences (i.e., the weights that they learned to give to different attributes during decision-making). Next, we demonstrate that these LLMs can be fine-tuned to explain their decision-making even more accurately. Finally, we demonstrate that this training generalizes: It improves the ability of the models to accurately explain what they are doing as they make other complex decisions, not just decisions they have learned to make via fine-tuning. This work is a step towards training LLMs to accurately and broadly report on their own internal processes -- a possibility that would yield substantial benefits for interpretability, control, and safety.
