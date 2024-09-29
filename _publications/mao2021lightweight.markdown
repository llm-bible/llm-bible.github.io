---
layout: publication
title: Lightweight Cross45;lingual Sentence Representation Learning
authors: Mao Zhuoyuan, Gupta Prakhar, Wang Pei, Chu Chenhui, Jaggi Martin, Kurohashi Sadao
conference: "Arxiv"
year: 2021
bibkey: mao2021lightweight
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2105.13856"}
tags: ['BERT', 'Masked Language Model', 'Model Architecture', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
Large45;scale models for learning fixed45;dimensional cross45;lingual sentence representations like LASER (Artetxe and Schwenk 2019b) lead to significant improvement in performance on downstream tasks. However further increases and modifications based on such large45;scale models are usually impractical due to memory limitations. In this work we introduce a lightweight dual45;transformer architecture with just 2 layers for generating memory45;efficient cross45;lingual sentence representations. We explore different training tasks and observe that current cross45;lingual training tasks leave a lot to be desired for this shallow architecture. To ameliorate this we propose a novel cross45;lingual language model which combines the existing single45;word masked language model with the newly proposed cross45;lingual token45;level reconstruction task. We further augment the training task by the introduction of two computationally45;lite sentence45;level contrastive learning tasks to enhance the alignment of cross45;lingual sentence representation space which compensates for the learning bottleneck of the lightweight transformer for generative tasks. Our comparisons with competing models on cross45;lingual sentence retrieval and multilingual document classification confirm the effectiveness of the newly proposed training tasks for a shallow model.
