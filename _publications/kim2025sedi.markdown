---
layout: publication
title: 'Sedi-instruct: Enhancing Alignment Of Language Models Through Self-directed Instruction Generation'
authors: Jungwoo Kim, Minsang Kim, Sungjin Lee
conference: "Arxiv"
year: 2025
bibkey: kim2025sedi
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.04774"}
tags: ['Training Techniques', 'Tools', 'GPT', 'Model Architecture']
---
The rapid evolution of Large Language Models (LLMs) has enabled the industry
to develop various AI-based services. Instruction tuning is considered
essential in adapting foundation models for target domains to provide
high-quality services to customers. A key challenge in instruction tuning is
obtaining high-quality instruction data. Self-Instruct, which automatically
generates instruction data using ChatGPT APIs, alleviates the data scarcity
problem. To improve the quality of instruction data, Self-Instruct discards
many of the instructions generated from ChatGPT, even though it is inefficient
in terms of cost owing to many useless API calls. To generate high-quality
instruction data at a low cost, we propose a novel data generation framework,
Self-Direct Instruction generation (SeDi-Instruct), which employs
diversity-based filtering and iterative feedback task generation.
Diversity-based filtering maintains model accuracy without excessively
discarding low-quality generated instructions by enhancing the diversity of
instructions in a batch. This reduces the cost of synthesizing instruction
data. The iterative feedback task generation integrates instruction generation
and training tasks and utilizes information obtained during the training to
create high-quality instruction sets. Our results show that SeDi-Instruct
enhances the accuracy of AI models by 5.2%, compared with traditional methods,
while reducing data generation costs by 36%.
