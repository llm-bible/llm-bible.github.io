---
layout: publication
title: 'Remamba: Equip Mamba With Effective Long-sequence Modeling'
authors: Yuan Danlong, Liu Jiahao, Li Bei, Zhang Huishuai, Wang Jingang, Cai Xunliang, Zhao Dongyan
conference: "Arxiv"
year: 2024
bibkey: yuan2024equip
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.15496"}
tags: ['Efficiency And Optimization', 'Model Architecture', 'Pretraining Methods', 'Transformer']
---
While the Mamba architecture demonstrates superior inference efficiency and
competitive performance on short-context natural language processing (NLP)
tasks, empirical evidence suggests its capacity to comprehend long contexts is
limited compared to transformer-based models. In this study, we investigate the
long-context efficiency issues of the Mamba models and propose ReMamba, which
enhances Mamba's ability to comprehend long contexts. ReMamba incorporates
selective compression and adaptation techniques within a two-stage re-forward
process, incurring minimal additional inference costs overhead. Experimental
results on the LongBench and L-Eval benchmarks demonstrate ReMamba's efficacy,
improving over the baselines by 3.2 and 1.6 points, respectively, and attaining
performance almost on par with same-size transformer models.
