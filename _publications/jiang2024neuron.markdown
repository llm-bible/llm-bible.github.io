---
layout: publication
title: 'Neuron-level Sequential Editing For Large Language Models'
authors: Houcheng Jiang, Junfeng Fang, Tianyu Zhang, An Zhang, Ruipeng Wang, Tao Liang, Xiang Wang
conference: "Arxiv"
year: 2024
bibkey: jiang2024neuron
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.04045'}
  - {name: "Code", url: 'https://github.com/jianghoucheng/NSE'}
tags: ['Reinforcement Learning', 'Has Code', 'Training Techniques']
---
This work explores sequential model editing in large language models (LLMs),
a critical task that involves modifying internal knowledge within LLMs
continuously through multi-round editing, each incorporating updates or
corrections to adjust the model outputs without the need for costly retraining.
Existing model editing methods, especially those that alter model parameters,
typically focus on single-round editing and often face significant challenges
in sequential model editing-most notably issues of model forgetting and
failure. To address these challenges, we introduce a new model editing method,
namely \textbf\{N\}euron-level \textbf\{S\}equential \textbf\{E\}diting (NSE),
tailored for supporting sequential model editing. Specifically, we optimize the
target layer's hidden states using the model's original weights to prevent
model failure. Furthermore, we iteratively select neurons in multiple layers
for editing based on their activation values to mitigate model forgetting. Our
empirical experiments demonstrate that NSE significantly outperforms current
modifying parameters model editing methods, marking a substantial advancement
in the field of sequential model editing. Our code is released on
\url\{https://github.com/jianghoucheng/NSE\}.
