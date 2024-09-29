---
layout: publication
title: Contrastive Learning With Bidirectional Transformers For Sequential Recommendation
authors: Du Hanwen, Shi Hui, Zhao Pengpeng, Wang Deqing, Sheng Victor S., Liu Yanchi, Liu Guanfeng, Zhao Lei
conference: "Arxiv"
year: 2022
bibkey: du2022contrastive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2208.03895"}
tags: ['BERT', 'Model Architecture', 'Pretraining Methods', 'Tools', 'Transformer']
---
Contrastive learning with Transformer45;based sequence encoder has gained predominance for sequential recommendation. It maximizes the agreements between paired sequence augmentations that share similar semantics. However existing contrastive learning approaches in sequential recommendation mainly center upon left45;to45;right unidirectional Transformers as base encoders which are suboptimal for sequential recommendation because user behaviors may not be a rigid left45;to45;right sequence. To tackle that we propose a novel framework named textbf123;C125;ontrastive learning with textbf123;Bi125;directional textbf123;T125;ransformers for sequential recommendation (textbf123;CBiT125;). Specifically we first apply the slide window technique for long user sequences in bidirectional Transformers which allows for a more fine45;grained division of user sequences. Then we combine the cloze task mask and the dropout mask to generate high45;quality positive samples and perform multi45;pair contrastive learning which demonstrates better performance and adaptability compared with the normal one45;pair contrastive learning. Moreover we introduce a novel dynamic loss reweighting strategy to balance between the cloze task loss and the contrastive loss. Experiment results on three public benchmark datasets show that our model outperforms state45;of45;the45;art models for sequential recommendation.
