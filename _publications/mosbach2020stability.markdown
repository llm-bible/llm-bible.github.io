---
layout: publication
title: On The Stability Of Fine45;tuning BERT Misconceptions Explanations And Strong Baselines
authors: Mosbach Marius, Andriushchenko Maksym, Klakow Dietrich
conference: "Arxiv"
year: 2020
bibkey: mosbach2020stability
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2006.04884"}
  - {name: "Code", url: "https://github.com/uds&#45;lsv/bert&#45;stable&#45;fine&#45;tuning"}
tags: ['BERT', 'Efficiency And Optimization', 'Has Code', 'Interpretability And Explainability', 'Model Architecture', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
Fine45;tuning pre45;trained transformer45;based language models such as BERT has become a common practice dominating leaderboards across various NLP benchmarks. Despite the strong empirical performance of fine45;tuned models fine45;tuning is an unstable process training the same model with multiple random seeds can result in a large variance of the task performance. Previous literature (Devlin et al. 2019; Lee et al. 2020; Dodge et al. 2020) identified two potential reasons for the observed instability catastrophic forgetting and small size of the fine45;tuning datasets. In this paper we show that both hypotheses fail to explain the fine45;tuning instability. We analyze BERT RoBERTa and ALBERT fine45;tuned on commonly used datasets from the GLUE benchmark and show that the observed instability is caused by optimization difficulties that lead to vanishing gradients. Additionally we show that the remaining variance of the downstream task performance can be attributed to differences in generalization where fine45;tuned models with the same training loss exhibit noticeably different test performance. Based on our analysis we present a simple but strong baseline that makes fine45;tuning BERT45;based models significantly more stable than the previously proposed approaches. Code to reproduce our results is available online https://github.com/uds&#45;lsv/bert&#45;stable&#45;fine&#45;tuning.
