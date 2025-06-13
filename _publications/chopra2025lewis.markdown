---
layout: publication
title: 'LEWIS (layer Wise Sparsity) -- A Training Free Guided Model Merging Approach'
authors: Hetarth Chopra, Vidhi Rambhia, Vikram Adve
conference: "Arxiv"
year: 2025
bibkey: chopra2025lewis
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.03874'}
tags: ['Efficiency and Optimization', 'Tools', 'Training Techniques', 'Merging', 'Pruning']
---
As specialized large language models (LLMs) become increasingly prevalent,
model merging methods are being used to combine them to create a single
multi-task model without requiring any additional data or training. However,
these approaches fall short when the objective of merging is to increase the
downstream model's performance on a particular task-specific benchmark. In this
work, we propose LEWIS (Layer Wise Sparsity), a guided model-merging framework
that uses activation-based layer importance to dynamically adjust layer-wise
task-vector sparsity required for the merge process. LEWIS uses a calibration
dataset to prioritize critical layers during the task-vector pruning process
required for model merging. This approach guides existing merging methods by
preserving essential layer-wise task-specific knowledge while ensuring the
merged model performs the best at benchmarks resembling the calibration
dataset. Our experiments demonstrate the effectiveness of LEWIS with
performance improvements of code instruction-following and math-solving models
created through model merging up to 4 percent and 11.3 percent, respectively,
outperforming unguided data-less model merging approaches that use
uniform-sparsity.
