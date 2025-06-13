---
layout: publication
title: 'Bjtu-wechat''s Systems For The WMT22 Chat Translation Task'
authors: Yunlong Liang, Fandong Meng, Jinan Xu, Yufeng Chen, Jie Zhou
conference: "Arxiv"
year: 2022
bibkey: liang2022bjtu
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2211.15009"}
tags: ['Fine-Tuning', 'Transformer', 'Pre-Training', 'Efficiency and Optimization', 'Model Architecture', 'WMT', 'Training Techniques', 'Pretraining Methods', 'Prompting', 'Distillation']
---
This paper introduces the joint submission of the Beijing Jiaotong University
and WeChat AI to the WMT'22 chat translation task for English-German. Based on
the Transformer, we apply several effective variants. In our experiments, we
utilize the pre-training-then-fine-tuning paradigm. In the first pre-training
stage, we employ data filtering and synthetic data generation (i.e.,
back-translation, forward-translation, and knowledge distillation). In the
second fine-tuning stage, we investigate speaker-aware in-domain data
generation, speaker adaptation, prompt-based context modeling, target denoising
fine-tuning, and boosted self-COMET-based model ensemble. Our systems achieve
0.810 and 0.946 COMET scores. The COMET scores of English-German and
German-English are the highest among all submissions.
