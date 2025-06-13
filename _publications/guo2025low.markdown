---
layout: publication
title: 'Nlora: Nystr\"om-initiated Low-rank Adaptation For Large Language Models'
authors: Chenlu Guo, Yuan Wu, Yi Chang
conference: "Arxiv"
year: 2025
bibkey: guo2025low
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.14482"}
tags: ['Fine-Tuning', 'Efficiency and Optimization', 'Applications', 'RAG', 'Training Techniques', 'Pretraining Methods']
---
Parameter-efficient fine-tuning (PEFT) is essential for adapting large
language models (LLMs), with low-rank adaptation (LoRA) being the most popular
approach. However, LoRA suffers from slow convergence, and some recent LoRA
variants, such as PiSSA, primarily rely on Singular Value Decomposition (SVD)
for initialization, leading to expensive computation. To mitigate these
problems, we use the Nystr\"om method, which follows a three-matrix
manipulation. We first introduce StructuredLoRA (SLoRA), which investigates
adding a small intermediate matrix between the low-rank matrices A and B.
Secondly, we propose Nystr\"omLoRA (NLoRA), which leverages Nystr\"om-based
initialization for SLoRA to improve its effectiveness and efficiency. Finally,
we propose IntermediateTune (IntTune), which explores fine-tuning exclusively
on the intermediate matrix of NLoRA to further boost LLM efficiency. We
evaluate our methods on five natural language generation (NLG) tasks and eight
natural language understanding (NLU) tasks. On GSM8K, SLoRA and NLoRA achieve
accuracies of 56.48% and 57.70%, surpassing LoRA by 33.52% and 36.41%, with
only 3.67 million additional trainable parameters. IntTune improves average NLG
performance over LoRA by 7.45% while using only 1.25% of its parameters. These
results demonstrate the efficiency and effectiveness of our approach in
enhancing model performance with minimal parameter overhead.
