---
layout: publication
title: 'Reducing Distraction In Long-context Language Models By Focused Learning'
authors: Zijun Wu, Bingyuan Liu, Ran Yan, Lei Chen, Thomas Delteil
conference: "Arxiv"
year: 2024
bibkey: wu2024reducing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2411.05928'}
tags: ['Fine-Tuning', 'Training Techniques', 'Pretraining Methods']
---
Recent advancements in Large Language Models (LLMs) have significantly
enhanced their capacity to process long contexts. However, effectively
utilizing this long context remains a challenge due to the issue of
distraction, where irrelevant information dominates lengthy contexts, causing
LLMs to lose focus on the most relevant segments. To address this, we propose a
novel training method that enhances LLMs' ability to discern relevant
information through a unique combination of retrieval-based data augmentation
and contrastive learning. Specifically, during fine-tuning with long contexts,
we employ a retriever to extract the most relevant segments, serving as
augmented inputs. We then introduce an auxiliary contrastive learning objective
to explicitly ensure that outputs from the original context and the retrieved
sub-context are closely aligned. Extensive experiments on long single-document
and multi-document QA benchmarks demonstrate the effectiveness of our proposed
method.
