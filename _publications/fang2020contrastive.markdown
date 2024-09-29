---
layout: publication
title: CERT: Contrastive Self-supervised Learning For Language Understanding
authors: Fang Hongchao, Wang Sicheng, Zhou Meng, Ding Jiayuan, Xie Pengtao
conference: "Arxiv"
year: 2020
bibkey: fang2020contrastive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2005.12766"}
  - {name: "Code", url: "https://github.com/UCSD-AI4H/CERT"}
tags: ['Applications', 'BERT', 'GPT', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Training Techniques', 'Transformer']
---
Pretrained language models such as BERT GPT have shown great effectiveness in language understanding. The auxiliary predictive tasks in existing pretraining approaches are mostly defined on tokens thus may not be able to capture sentence-level semantics very well. To address this issue we propose CERT Contrastive self-supervised Encoder Representations from Transformers which pretrains language representation models using contrastive self-supervised learning at the sentence level. CERT creates augmentations of original sentences using back-translation. Then it finetunes a pretrained language encoder (e.g. BERT) by predicting whether two augmented sentences originate from the same sentence. CERT is simple to use and can be flexibly plugged into any pretraining-finetuning NLP pipeline. We evaluate CERT on 11 natural language understanding tasks in the GLUE benchmark where CERT outperforms BERT on 7 tasks achieves the same performance as BERT on 2 tasks and performs worse than BERT on 2 tasks. On the averaged score of the 11 tasks CERT outperforms BERT. The data and code are available at https://github.com/UCSD-AI4H/CERT"
