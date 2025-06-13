---
layout: publication
title: 'What Do Learning Dynamics Reveal About Generalization In LLM Reasoning?'
authors: Katie Kang, Amrith Setlur, Dibya Ghosh, Jacob Steinhardt, Claire Tomlin, Sergey Levine, Aviral Kumar
conference: "Arxiv"
year: 2024
bibkey: kang2024what
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2411.07681'}
tags: ['Efficiency and Optimization', 'Training Techniques']
---
Despite the remarkable capabilities of modern large language models (LLMs),
the mechanisms behind their problem-solving abilities remain elusive. In this
work, we aim to better understand how the learning dynamics of LLM finetuning
shapes downstream generalization. Our analysis focuses on reasoning tasks,
whose problem structure allows us to distinguish between memorization (the
exact replication of reasoning steps from the training data) and performance
(the correctness of the final solution). We find that a model's generalization
behavior can be effectively characterized by a training metric we call
pre-memorization train accuracy: the accuracy of model samples on training
queries before they begin to copy the exact reasoning steps from the training
set. On the dataset level, this metric is able to reliably predict test
accuracy, achieving \\(R^2\\) of around or exceeding 0.9 across various models
(Llama3 8, Gemma2 9B), datasets (GSM8k, MATH), and training configurations. On
a per-example level, this metric is also indicative of whether individual model
predictions are robust to perturbations in the training query. By connecting a
model's learning behavior to its generalization, pre-memorization train
accuracy can guide targeted improvements to training strategies. We focus on
data curation as an example, and show that prioritizing examples with low
pre-memorization accuracy leads to 1.5-2x improvements in data efficiency
compared to i.i.d. data scaling, and outperforms other standard data curation
techniques.
