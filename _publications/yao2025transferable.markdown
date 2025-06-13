---
layout: publication
title: 'Transferable Text Data Distillation By Trajectory Matching'
authors: Rong Yao, Hailin Hu, Yifei Fu, Hanting Chen, Wenyi Fang, Fanyi Du, Kai Han, Yunhe Wang
conference: "Arxiv"
year: 2025
bibkey: yao2025transferable
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.09818'}
tags: ['Security', 'Efficiency and Optimization', 'Model Architecture', 'Distillation', 'Training Techniques', 'Fine-Tuning', 'Prompting']
---
In the realm of large language model (LLM), as the size of large models
increases, it also brings higher training costs. There is a urgent need to
minimize the data size in LLM training. Compared with data selection method,
the data distillation method aims to synthesize a small number of data samples
to achieve the training effect of the full data set and has better flexibility.
Despite its successes in computer vision, the discreteness of text data has
hitherto stymied its exploration in natural language processing (NLP). In this
work, we proposed a method that involves learning pseudo prompt data based on
trajectory matching and finding its nearest neighbor ID to achieve
cross-architecture transfer. During the distillation process, we introduce a
regularization loss to improve the robustness of our distilled data. To our
best knowledge, this is the first data distillation work suitable for text
generation tasks such as instruction tuning. Evaluations on two benchmarks,
including ARC-Easy and MMLU instruction tuning datasets, established the
superiority of our distillation approach over the SOTA data selection method
LESS. Furthermore, our method demonstrates a good transferability over LLM
structures (i.e., OPT to Llama).
