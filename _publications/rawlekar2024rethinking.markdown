---
layout: publication
title: 'Rethinking Prompting Strategies For Multi-label Recognition With Partial Annotations'
authors: Samyak Rawlekar, Shubhang Bhatnagar, Narendra Ahuja
conference: "Arxiv"
year: 2024
bibkey: rawlekar2024rethinking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.08381"}
tags: ['RAG', 'Training Techniques', 'Multimodal Models', 'Prompting']
---
Vision-language models (VLMs) like CLIP have been adapted for Multi-Label
Recognition (MLR) with partial annotations by leveraging prompt-learning, where
positive and negative prompts are learned for each class to associate their
embeddings with class presence or absence in the shared vision-text feature
space. While this approach improves MLR performance by relying on VLM priors,
we hypothesize that learning negative prompts may be suboptimal, as the
datasets used to train VLMs lack image-caption pairs explicitly focusing on
class absence. To analyze the impact of positive and negative prompt learning
on MLR, we introduce PositiveCoOp and NegativeCoOp, where only one prompt is
learned with VLM guidance while the other is replaced by an embedding vector
learned directly in the shared feature space without relying on the text
encoder. Through empirical analysis, we observe that negative prompts degrade
MLR performance, and learning only positive prompts, combined with learned
negative embeddings (PositiveCoOp), outperforms dual prompt learning
approaches. Moreover, we quantify the performance benefits that prompt-learning
offers over a simple vision-features-only baseline, observing that the baseline
displays strong performance comparable to dual prompt learning approach
(DualCoOp), when the proportion of missing labels is low, while requiring half
the training compute and 16 times fewer parameters
