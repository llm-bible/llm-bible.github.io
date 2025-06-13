---
layout: publication
title: 'Galore\(+\): Boosting Low-rank Adaptation For Llms With Cross-head Projection'
authors: Xutao Liao, Shaohui Li, Yuhui Xu, Zhi Li, Yu Liu, You He
conference: "Arxiv"
year: 2024
bibkey: liao2024boosting
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.19820'}
tags: ['Attention Mechanism', 'Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Fine-Tuning', 'Pretraining Methods']
---
Recent low-rank training methods, such as GaLore, have significantly reduced
the memory required to optimize large language models (LLMs). However, these
methods often suffer from time-consuming low-rank projection estimations. In
particular, the singular value decomposition (SVD) in GaLore can consume more
than 80% of the total training time. To address this issue, we propose
GaLore\\(+\\), which uses cross-head low-rank projection to reduce the substantial
time consumption in estimating low-rank projections for multi-head attention.
In addition, we employ randomized subspace iteration to achieve fast SVD. To
further enhance performance, we propose sparsely coded residuals to reduce the
errors caused by low-rank approximation on the first- and second-order moments
of the optimizers and weight updates. We evaluate GaLore\\(+\\) on arithmetic
reasoning and natural language generation datasets. Our experiments demonstrate
that GaLore\\(+\\) delivers superior performance while achieving approximately
\\(4\times\\) fine-tuning speed compared to vanilla GaLore.
