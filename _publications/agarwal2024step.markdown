---
layout: publication
title: 'Step-by-step Unmasking For Parameter-efficient Fine-tuning Of Large Language Models'
authors: Aradhye Agarwal, Suhas K Ramesh, Ayan Sengupta, Tanmoy Chakraborty
conference: "Arxiv"
year: 2024
bibkey: agarwal2024step
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2408.14470'}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Applications', 'Fine-Tuning', 'Pruning', 'Ethics and Bias', 'Pretraining Methods']
---
Fine-tuning large language models (LLMs) on downstream tasks requires
substantial computational resources. A class of parameter-efficient fine-tuning
(PEFT) aims to mitigate these computational challenges by selectively
fine-tuning only a small fraction of the model parameters. Although
computationally efficient, these techniques often fail to match the performance
of fully fine-tuned models, primarily due to inherent biases introduced during
parameter selection. Traditional selective PEFT techniques use a fixed set of
parameters based on a predefined budget (a process also known as unmasking),
failing to capture parameter importance dynamically and often ending up
exceeding the budget. We introduce \\(\text\{ID\}^3\\), a novel selective PEFT method
that calculates parameter importance continually and dynamically unmasks
parameters by balancing exploration and exploitation in parameter selection.
Our empirical study on 15 tasks spanning natural language understanding and
generative tasks demonstrates the effectiveness of our method compared to
fixed-masking-based PEFT techniques. We analytically show that \\(\text\{ID\}^3\\)
reduces the number of gradient updates by a factor of two, enhancing
computational efficiency. \\(\text\{ID\}^3\\) is robust to random initialization of
neurons and, therefore, can be seamlessly integrated into existing additive and
reparametrization-based PEFT modules such as adapters and LoRA for dynamic
sparsification.
