---
layout: publication
title: Exploring Extreme Parameter Compression For Pre45;trained Language Models
authors: Ren Yuxin, Wang Benyou, Shang Lifeng, Jiang Xin, Liu Qun
conference: "Arxiv"
year: 2022
bibkey: ren2022exploring
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2205.10036"}
tags: ['Attention Mechanism', 'BERT', 'Distillation', 'Efficiency And Optimization', 'Model Architecture', 'Pretraining Methods', 'Transformer']
---
Recent work explored the potential of large45;scale Transformer45;based pre45;trained models especially Pre45;trained Language Models (PLMs) in natural language processing. This raises many concerns from various perspectives e.g. financial costs and carbon emissions. Compressing PLMs like BERT with negligible performance loss for faster inference and cheaper deployment has attracted much attention. In this work we aim to explore larger compression ratios for PLMs among which tensor decomposition is a potential but under45;investigated one. Two decomposition and reconstruction protocols are further proposed to improve the effectiveness and efficiency during compression. Our compressed BERT with 123;1125;/123;7125; parameters in Transformer layers performs on45;par with sometimes slightly better than the original BERT in GLUE benchmark. A tiny version achieves 96.737; performance of BERT45;base with 123;1125;/123;48125; encoder parameters (i.e. less than 2M parameters excluding the embedding layer) and 2.7 × faster on inference. To show that the proposed method is orthogonal to existing compression methods like knowledge distillation we also explore the benefit of the proposed method on a distilled BERT.
