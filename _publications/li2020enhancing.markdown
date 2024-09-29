---
layout: publication
title: 'Enhancing Dialogue Generation Via Multi-level Contrastive Learning'
authors: Li Xin, Li Piji, Wang Yan, Liu Xiaojiang, Lam Wai
conference: "Arxiv"
year: 2020
bibkey: li2020enhancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2009.09147"}
tags: ['Attention Mechanism', 'Efficiency And Optimization', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Training Techniques']
---
Most of the existing works for dialogue generation are data-driven models trained directly on corpora crawled from websites. They mainly focus on improving the model architecture to produce better responses but pay little attention to considering the quality of the training data contrastively. In this paper we propose a multi-level contrastive learning paradigm to model the fine-grained quality of the responses with respect to the query. A Rank-aware Calibration (RC) network is designed to construct the multi-level contrastive optimization objectives. Since these objectives are calculated based on the sentence level which may erroneously encourage/suppress the generation of uninformative/informative words. To tackle this incidental issue on one hand we design an exquisite token-level strategy for estimating the instance loss more accurately. On the other hand we build a Knowledge Inference (KI) component to capture the keyword knowledge from the reference during training and exploit such information to encourage the generation of informative words. We evaluate the proposed model on a carefully annotated dialogue dataset and the results suggest that our model can generate more relevant and diverse responses compared to the baseline models.
