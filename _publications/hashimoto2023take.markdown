---
layout: publication
title: 'Take One Step At A Time To Know Incremental Utility Of Demonstration: An Analysis On Reranking For Few-shot In-context Learning'
authors: Kazuma Hashimoto, Karthik Raman, Michael Bendersky
conference: "Arxiv"
year: 2023
bibkey: hashimoto2023take
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.09619"}
tags: ['Reinforcement Learning', 'Training Techniques', 'Few-Shot', 'Prompting', 'In-Context Learning']
---
In-Context Learning (ICL) is an emergent capability of Large Language Models
(LLMs). Only a few demonstrations enable LLMs to be used as blackbox for new
tasks. Previous studies have shown that using LLMs' outputs as labels is
effective in training models to select demonstrations. Such a label is expected
to estimate utility of a demonstration in ICL; however, it has not been well
understood how different labeling strategies affect results on target tasks.
This paper presents an analysis on different utility functions by focusing on
LLMs' output probability given ground-truth output, and task-specific reward
given LLMs' prediction. Unlike the previous work, we introduce a novel labeling
method, incremental utility, which estimates how much incremental knowledge is
brought into the LLMs by a demonstration. We conduct experiments with
instruction-tuned LLMs on binary/multi-class classification, segmentation, and
translation across Arabic, English, Finnish, Japanese, and Spanish. Our results
show that (1) the probability is effective when the probability values are
distributed across the whole value range (on the classification tasks), and (2)
the downstream metric is more robust when nuanced reward values are provided
with long outputs (on the segmentation and translation tasks). We then show
that the proposed incremental utility further helps ICL by contrasting how the
LLMs perform with and without the demonstrations.
