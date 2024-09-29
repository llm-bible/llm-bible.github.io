---
layout: publication
title: Distilled Dual45;encoder Model For Vision45;language Understanding
authors: Wang Zekun, Wang Wenhui, Zhu Haichao, Liu Ming, Qin Bing, Wei Furu
conference: "Arxiv"
year: 2021
bibkey: wang2021distilled
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2112.08723"}
  - {name: "Code", url: "https://github.com/kugwzk/Distilled&#45;DualEncoder"}
tags: ['Applications', 'Attention Mechanism', 'Distillation', 'Efficiency And Optimization', 'Has Code', 'Merging', 'Model Architecture', 'Tools', 'Training Techniques']
---
We propose a cross45;modal attention distillation framework to train a dual45;encoder model for vision45;language understanding tasks such as visual reasoning and visual question answering. Dual45;encoder models have a faster inference speed than fusion45;encoder models and enable the pre45;computation of images and text during inference. However the shallow interaction module used in dual45;encoder models is insufficient to handle complex vision45;language understanding tasks. In order to learn deep interactions of images and text we introduce cross45;modal attention distillation which uses the image45;to45;text and text45;to45;image attention distributions of a fusion45;encoder model to guide the training of our dual45;encoder model. In addition we show that applying the cross45;modal attention distillation for both pre45;training and fine45;tuning stages achieves further improvements. Experimental results demonstrate that the distilled dual45;encoder model achieves competitive performance for visual reasoning visual entailment and visual question answering tasks while enjoying a much faster inference speed than fusion45;encoder models. Our code and models will be publicly available at https://github.com/kugwzk/Distilled&#45;DualEncoder.
