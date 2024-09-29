---
layout: publication
title: MKD A Multi45;task Knowledge Distillation Approach For Pretrained Language Models
authors: Liu Linqing, Wang Huan, Lin Jimmy, Socher Richard, Xiong Caiming
conference: "Arxiv"
year: 2019
bibkey: liu2019multi
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1911.03588"}
tags: ['BERT', 'Distillation', 'Efficiency And Optimization', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Tools', 'Transformer']
---
Pretrained language models have led to significant performance gains in many NLP tasks. However the intensive computing resources to train such models remain an issue. Knowledge distillation alleviates this problem by learning a light45;weight student model. So far the distillation approaches are all task45;specific. In this paper we explore knowledge distillation under the multi45;task learning setting. The student is jointly distilled across different tasks. It acquires more general representation capacity through multi45;tasking distillation and can be further fine45;tuned to improve the model in the target domain. Unlike other BERT distillation methods which specifically designed for Transformer45;based architectures we provide a general learning framework. Our approach is model agnostic and can be easily applied on different future teacher model architectures. We evaluate our approach on a Transformer45;based and LSTM based student model. Compared to a strong similarly LSTM45;based approach we achieve better quality under the same computational constraints. Compared to the present state of the art we reach comparable results with much faster inference speed.
