---
layout: publication
title: 'Large Language Models Are Overparameterized Text Encoders'
authors: Thennal D K, Tim Fischer, Chris Biemann
conference: "Arxiv"
year: 2024
bibkey: k2024large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.14578"}
tags: ['RAG', 'Training Techniques', 'Efficiency and Optimization', 'Pruning']
---
Large language models (LLMs) demonstrate strong performance as text embedding
models when finetuned with supervised contrastive training. However, their
large size balloons inference time and memory requirements. In this paper, we
show that by pruning the last \\(p%\\) layers of an LLM before supervised training
for only 1000 steps, we can achieve a proportional reduction in memory and
inference time. We evaluate four different state-of-the-art LLMs on text
embedding tasks and find that our method can prune up to 30% of layers with
negligible impact on performance and up to 80% with only a modest drop. With
only three lines of code, our method is easily implemented in any pipeline for
transforming LLMs to text encoders. We also propose \\(\text\{L\}^3 \text\{Prune\}\\),
a novel layer-pruning strategy based on the model's initial loss that provides
two optimal pruning configurations: a large variant with negligible performance
loss and a small variant for resource-constrained settings. On average, the
large variant prunes 21% of the parameters with a \\(-0.3\\) performance drop, and
the small variant only suffers from a \\(-5.1\\) decrease while pruning 74% of the
model. We consider these results strong evidence that LLMs are
overparameterized for text embedding tasks, and can be easily pruned.
