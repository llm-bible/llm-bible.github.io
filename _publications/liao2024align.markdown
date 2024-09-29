---
layout: publication
title: Align And Aggregate Compositional Reasoning With Video Alignment And Answer Aggregation For Video Question45;answering
authors: Liao Zhaohe, Li Jiangtong, Niu Li, Zhang Liqing
conference: "CVPR"
year: 2024
bibkey: liao2024align
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.03008"}
tags: ['Pretraining Methods', 'Reinforcement Learning', 'Tools']
---
Despite the recent progress made in Video Question45;Answering (VideoQA) these methods typically function as black45;boxes making it difficult to understand their reasoning processes and perform consistent compositional reasoning. To address these challenges we propose a textit123;model45;agnostic125; Video Alignment and Answer Aggregation (VA^123;3125;) framework which is capable of enhancing both compositional consistency and accuracy of existing VidQA methods by integrating video aligner and answer aggregator modules. The video aligner hierarchically selects the relevant video clips based on the question while the answer aggregator deduces the answer to the question based on its sub45;questions with compositional consistency ensured by the information flow along question decomposition graph and the contrastive learning strategy. We evaluate our framework on three settings of the AGQA45;Decomp dataset with three baseline methods and propose new metrics to measure the compositional consistency of VidQA methods more comprehensively. Moreover we propose a large language model (LLM) based automatic question decomposition pipeline to apply our framework to any VidQA dataset. We extend MSVD and NExT45;QA datasets with it to evaluate our VA^3 framework on broader scenarios. Extensive experiments show that our framework improves both compositional consistency and accuracy of existing methods leading to more interpretable real45;world VidQA models.
