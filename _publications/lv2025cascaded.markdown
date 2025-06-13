---
layout: publication
title: 'Cascaded Self-evaluation Augmented Training For Lightweight Multimodal Llms'
authors: Zheqi Lv, Wenkai Wang, Jiawei Wang, Shengyu Zhang, Fei Wu
conference: "Arxiv"
year: 2025
bibkey: lv2025cascaded
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2501.05662'}
tags: ['RAG', 'Training Techniques', 'Fine-Tuning', 'Prompting', 'Multimodal Models', 'Pretraining Methods']
---
Efficient Multimodal Large Language Models (EMLLMs) can improve performance
through Chain-of-Thought (CoT) reasoning, but they have poor self-evaluation
capabilities during the CoT reasoning process. This is due to their tendency to
simplify the reasoning process and the degradation of self-evaluation ability
during downstream task fine-tuning. To address this, we intuitively propose
\textit\{Self-Evaluation Augmented Training (SEAT)\}, which uses more powerful
EMLLMs to evaluate CoT reasoning data. The evaluation data is then used to
train EMLLMs. However, due to the difficulties EMLLMs face with processing long
token input-output sequences, and the degradation of self-evaluation ability as
a basis for CoT reasoning, the SEAT method is not fully adapted. Therefore, we
further propose \textit\{Cascaded Self-Evaluation Augmented Training
(Cas-SEAT)\}, which converts long prompts into cascaded short prompts, each
focusing on a specific task. Additionally, we mix CoT reasoning and
self-evaluation data to preserve its CoT reasoning ability while enhancing the
self-evaluation capability of EMLLMs. We also conduct \textit\{Double-level Data
Filtering (DDF)\}, which includes source data filtering and labeled data
filtering, using both manual selection and MLLMs for filtering. Cas-SEAT and
DDF work together to improve the performance of EMLLMs. Experiments show that
Cas-SEAT achieves an average improvement of 22.16% across multiple datasets,
and DDF significantly reduces the resource consumption of training
