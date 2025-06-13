---
layout: publication
title: 'Mamba State-space Models Are Lyapunov-stable Learners'
authors: John T. Halloran, Manbir Gulati, Paul F. Roysdon
conference: "Arxiv"
year: 2024
bibkey: halloran2024mamba
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2406.00209'}
tags: ['Transformer', 'Training Techniques', 'Model Architecture', 'Tools', 'Fine-Tuning', 'Prompting', 'In-Context Learning', 'Pretraining Methods']
---
Mamba state-space models (SSMs) were recently shown to outperform
state-of-the-art (SOTA) Transformer large language models (LLMs) across various
tasks. Despite subsequent widespread adaptation, little work has focused on
Mamba LLMs' amenability for fine-tuning frameworks ubiquitously used for
Transformer-based LLMs, e.g., mixed-precision fine-tuning (MPFT) and
parameter-efficient fine-tuning (PEFT). For the former, it currently remains an
open question whether Mamba's recurrent dynamics are robust to small input
changes, such as those encountered during MPFT. Using dynamical systems theory
(in particular, Lyapunov exponents), we answer this question in the
affirmative. We empirically validate this result through several experiments,
showing that Mamba SSMs are significantly more stable to changes introduced by
mixed-precision than comparable Transformers, even when both MPFT and PEFT are
combined. For PEFT, we show how targeting specific memory buffers in Mamba's
customized CUDA kernels for low-rank adaptation regularizes SSM parameters,
thus providing both parameter efficient learning and computational savings.
Finally, with both MPFT and PEFT enabled, we explore the impact of instruction
tuning Mamba SSMs for in-context learning (ICL) on natural language tasks.
While pretrained Mamba and Mamba-2 models only achieve 38% and 82%
(respectively) of the ICL improvements of comparable Transformer-based LLMs, we
show that instruction tuning allows Mamba models to narrow this gap to 81% and
Mamba-2 models to skyrocket over this gap to 132%.
