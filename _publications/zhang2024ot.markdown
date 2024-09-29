---
layout: publication
title: OT45;VP Optimal Transport45;guided Visual Prompting For Test45;time Adaptation
authors: Zhang Yunbei, Mehra Akshay, Hamm Jihun
conference: "Arxiv"
year: 2024
bibkey: zhang2024ot
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.09498"}
tags: ['Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'Prompting', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
Vision Transformers (ViTs) have demonstrated remarkable capabilities in learning representations but their performance is compromised when applied to unseen domains. Previous methods either engage in prompt learning during the training phase or modify model parameters at test time through entropy minimization. The former often overlooks unlabeled target data while the latter doesnt fully address domain shifts. In this work our approach Optimal Transport45;guided Test45;Time Visual Prompting (OT45;VP) handles these problems by leveraging prompt learning at test time to align the target and source domains without accessing the training process or altering pre45;trained model parameters. This method involves learning a universal visual prompt for the target domain by optimizing the Optimal Transport distance.OT45;VP with only four learned prompt tokens exceeds state45;of45;the45;art performance across three stylistic datasets45;PACS VLCS OfficeHome and one corrupted dataset ImageNet45;C. Additionally OT45;VP operates efficiently both in terms of memory and computation and is adaptable for extension to online settings.
