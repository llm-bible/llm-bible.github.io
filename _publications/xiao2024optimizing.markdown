---
layout: publication
title: 'Cora: Optimizing Low-rank Adaptation With Common Subspace Of Large Language Models'
authors: Xiaojun Xiao, Sen Shen, Qiming Bao, Hongfei Rong, Kairui Liu, Zhongsheng Wang, Jiamou Liu
conference: "Arxiv"
year: 2024
bibkey: xiao2024optimizing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.02119"}
tags: ['Fine-Tuning', 'Efficiency and Optimization', 'RAG', 'Training Techniques', 'Pretraining Methods']
---
In fine-tuning large language models (LLMs), conserving computational
resources while maintaining effectiveness and improving outcomes within the
same computational constraints is crucial. The Low-Rank Adaptation (LoRA)
strategy balances efficiency and performance in fine-tuning large models by
reducing the number of trainable parameters and computational costs. However,
current advancements in LoRA might be focused on its fine-tuning methodologies,
with not as much exploration as might be expected into further compression of
LoRA. Since most of LoRA's parameters might still be superfluous, this may lead
to unnecessary wastage of computational resources. In this paper, we propose
\textbf\{CoRA\}: leveraging shared knowledge to optimize LoRA training by
substituting its matrix \\(B\\) with a common subspace from large models. Our
two-fold method includes (1) Freezing the substitute matrix \\(B\\) to halve
parameters while training matrix \\(A\\) for specific tasks and (2) Using the
substitute matrix \\(B\\) as an enhanced initial state for the original matrix \\(B\\),
achieving improved results with the same parameters. Our experiments show that
the first approach achieves the same efficacy as the original LoRA fine-tuning
while being more efficient than halving parameters. At the same time, the
second approach has some improvements compared to LoRA's original fine-tuning
performance. They generally attest to the effectiveness of our work.
