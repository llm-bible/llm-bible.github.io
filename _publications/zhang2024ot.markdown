---
layout: publication
title: 'OT-VP: Optimal Transport-guided Visual Prompting For Test-time Adaptation'
authors: Yunbei Zhang, Akshay Mehra, Jihun Hamm
conference: "Arxiv"
year: 2024
bibkey: zhang2024ot
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2407.09498'}
tags: ['Transformer', 'RAG', 'Training Techniques', 'Model Architecture', 'Prompting', 'Multimodal Models', 'Reinforcement Learning', 'Pretraining Methods']
---
Vision Transformers (ViTs) have demonstrated remarkable capabilities in
learning representations, but their performance is compromised when applied to
unseen domains. Previous methods either engage in prompt learning during the
training phase or modify model parameters at test time through entropy
minimization. The former often overlooks unlabeled target data, while the
latter doesn't fully address domain shifts. In this work, our approach, Optimal
Transport-guided Test-Time Visual Prompting (OT-VP), handles these problems by
leveraging prompt learning at test time to align the target and source domains
without accessing the training process or altering pre-trained model
parameters. This method involves learning a universal visual prompt for the
target domain by optimizing the Optimal Transport distance.OT-VP, with only
four learned prompt tokens, exceeds state-of-the-art performance across three
stylistic datasets-PACS, VLCS, OfficeHome, and one corrupted dataset
ImageNet-C. Additionally, OT-VP operates efficiently, both in terms of memory
and computation, and is adaptable for extension to online settings.
