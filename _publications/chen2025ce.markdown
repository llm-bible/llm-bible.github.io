---
layout: publication
title: 'Ce-lora: Computation-efficient Lora Fine-tuning For Language Models'
authors: Guanduo Chen, Yutong He, Yipeng Hu, Kun Yuan, Binhang Yuan
conference: "Arxiv"
year: 2025
bibkey: chen2025ce
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.01378"}
tags: ['Fine-Tuning', 'Efficiency and Optimization', 'RAG', 'Training Techniques', 'Pretraining Methods']
---
Large Language Models (LLMs) demonstrate exceptional performance across
various tasks but demand substantial computational resources even for
fine-tuning computation. Although Low-Rank Adaptation (LoRA) significantly
alleviates memory consumption during fine-tuning, its impact on computational
cost reduction is limited. This paper identifies the computation of activation
gradients as the primary bottleneck in LoRA's backward propagation and
introduces the Computation-Efficient LoRA (CE-LoRA) algorithm, which enhances
computational efficiency while preserving memory efficiency. CE-LoRA leverages
two key techniques: Approximated Matrix Multiplication, which replaces dense
multiplications of large and complete matrices with sparse multiplications
involving only critical rows and columns, and the Double-LoRA technique, which
reduces error propagation in activation gradients. Theoretically, CE-LoRA
converges at the same rate as LoRA, \\( \mathcal\{O\}(1/\sqrt\{T\}) \\), where \\(T\\) is
the number of iteartions. Empirical evaluations confirm that CE-LoRA
significantly reduces computational costs compared to LoRA without notable
performance degradation.
