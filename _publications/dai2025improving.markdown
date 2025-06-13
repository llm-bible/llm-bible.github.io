---
layout: publication
title: 'Improving Influence-based Instruction Tuning Data Selection For Balanced Learning Of Diverse Capabilities'
authors: Qirun Dai, Dylan Zhang, Jiaqi W. Ma, Hao Peng
conference: "Arxiv"
year: 2025
bibkey: dai2025improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.12147"}
tags: ['Fine-Tuning', 'Tools', 'Efficiency and Optimization', 'Ethics and Bias', 'Training Techniques', 'Pretraining Methods']
---
Selecting appropriate training data is crucial for effective instruction
fine-tuning of large language models (LLMs), which aims to (1) elicit strong
capabilities, and (2) achieve balanced performance across a diverse range of
tasks. Influence-based methods show promise in achieving (1) by estimating the
contribution of each training example to the model's predictions, but often
struggle with (2). Our systematic investigation reveals that this
underperformance can be attributed to an inherent bias where certain tasks
intrinsically have greater influence than others. As a result, data selection
is often biased towards these tasks, not only hurting the model's performance
on others but also, counterintuitively, harms performance on these
high-influence tasks themselves.
  As a remedy, we propose BIDS, a Balanced and Influential Data Selection
algorithm. BIDS first normalizes influence scores of the training data, and
then iteratively balances data selection by choosing the training example with
the highest influence on the most underrepresented task. Experiments with both
Llama-3 and Mistral-v0.3 on seven benchmarks spanning five diverse capabilities
show that BIDS consistently outperforms both state-of-the-art influence-based
algorithms and other non-influence-based selection frameworks. Surprisingly,
training on a 15% subset selected by BIDS can even outperform full-dataset
training with a much more balanced performance. Our analysis further highlights
the importance of both instance-level normalization and iterative optimization
of selected data for balanced learning of diverse capabilities.
