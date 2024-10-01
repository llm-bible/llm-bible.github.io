---
layout: publication
title: 'Decoder Tuning: Efficient Language Understanding As Decoding'
authors: Cui Ganqu, Li Wentao, Ding Ning, Huang Longtao, Liu Zhiyuan, Sun Maosong
conference: "Arxiv"
year: 2022
bibkey: cui2022decoder
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2212.08408"}
tags: ['Applications', 'Efficiency And Optimization', 'Merging', 'Prompting', 'Tools']
---
With the evergrowing sizes of pre-trained models (PTMs), it has been an emerging practice to only provide the inference APIs for users, namely model-as-a-service (MaaS) setting. To adapt PTMs with model parameters frozen, most current approaches focus on the input side, seeking for powerful prompts to stimulate models for correct answers. However, we argue that input-side adaptation could be arduous due to the lack of gradient signals and they usually require thousands of API queries, resulting in high computation and time costs. In light of this, we present Decoder Tuning (DecT), which in contrast optimizes task-specific decoder networks on the output side. Specifically, DecT first extracts prompt-stimulated output scores for initial predictions. On top of that, we train an additional decoder network on the output representations to incorporate posterior data knowledge. By gradient-based optimization, DecT can be trained within several seconds and requires only one PTM query per sample. Empirically, we conduct extensive natural language understanding experiments and show that DecT significantly outperforms state-of-the-art algorithms with a \(200\times\) speed-up.
