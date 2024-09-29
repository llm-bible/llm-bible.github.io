---
layout: publication
title: Align Before Fuse Vision And Language Representation Learning With Momentum Distillation
authors: Li Junnan, Selvaraju Ramprasaath R., Gotmare Akhilesh Deepak, Joty Shafiq, Xiong Caiming, Hoi Steven
conference: "Arxiv"
year: 2021
bibkey: li2021align
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2107.07651"}
  - {name: "Code", url: "https://github.com/salesforce/ALBEF/"}
tags: ['Attention Mechanism', 'Distillation', 'Efficiency And Optimization', 'Has Code', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
Large45;scale vision and language representation learning has shown promising improvements on various vision45;language tasks. Most existing methods employ a transformer45;based multimodal encoder to jointly model visual tokens (region45;based image features) and word tokens. Because the visual tokens and word tokens are unaligned it is challenging for the multimodal encoder to learn image45;text interactions. In this paper we introduce a contrastive loss to ALign the image and text representations BEfore Fusing (ALBEF) them through cross45;modal attention which enables more grounded vision and language representation learning. Unlike most existing methods our method does not require bounding box annotations nor high45;resolution images. In order to improve learning from noisy web data we propose momentum distillation a self45;training method which learns from pseudo45;targets produced by a momentum model. We provide a theoretical analysis of ALBEF from a mutual information maximization perspective showing that different training tasks can be interpreted as different ways to generate views for an image45;text pair. ALBEF achieves state45;of45;the45;art performance on multiple downstream vision45;language tasks. On image45;text retrieval ALBEF outperforms methods that are pre45;trained on orders of magnitude larger datasets. On VQA and NLVR^2 ALBEF achieves absolute improvements of 2.3737; and 3.8437; compared to the state45;of45;the45;art while enjoying faster inference speed. Code and pre45;trained models are available at https://github.com/salesforce/ALBEF/.
