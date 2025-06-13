---
layout: publication
title: 'MLKD-BERT: Multi-level Knowledge Distillation For Pre-trained Language Models'
authors: Ying Zhang, Ziheng Yang, Shufan Ji
conference: "Arxiv"
year: 2024
bibkey: zhang2024mlkd
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.02775"}
tags: ['Efficiency and Optimization', 'Model Architecture', 'Tools', 'Distillation', 'Quantization', 'BERT', 'Applications', 'Attention Mechanism']
---
Knowledge distillation is an effective technique for pre-trained language
model compression. Although existing knowledge distillation methods perform
well for the most typical model BERT, they could be further improved in two
aspects: the relation-level knowledge could be further explored to improve
model performance; and the setting of student attention head number could be
more flexible to decrease inference time. Therefore, we are motivated to
propose a novel knowledge distillation method MLKD-BERT to distill multi-level
knowledge in teacher-student framework. Extensive experiments on GLUE benchmark
and extractive question answering tasks demonstrate that our method outperforms
state-of-the-art knowledge distillation methods on BERT. In addition, MLKD-BERT
can flexibly set student attention head number, allowing for substantial
inference time decrease with little performance drop.
