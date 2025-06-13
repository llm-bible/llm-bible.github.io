---
layout: publication
title: 'Xmodel-1.5: An 1b-scale Multilingual LLM'
authors: Wang Qun, Liu Yang, Lin Qingquan, Jiang Ling
conference: "Arxiv"
year: 2024
bibkey: qun2024xmodel
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.10083"}
  - {name: "Code", url: "https://github.com/XiaoduoAILab/XmodelLM-1.5"}
tags: ['Efficiency and Optimization', 'Has Code', 'Reinforcement Learning']
---
We introduce Xmodel-1.5, a 1-billion-parameter multilingual large language
model pretrained on 2 trillion tokens, designed for balanced performance and
scalability. Unlike most large models that use the BPE tokenizer, Xmodel-1.5
employs a custom unigram tokenizer with 65,280 tokens, optimizing both
efficiency and accuracy. The model delivers competitive results across multiple
languages, including Thai, Arabic, French, Chinese, and English, outperforming
Alibaba's PolyLM-1.7B on respective evaluation datasets. Xmodel-1.5 excels in
benchmarks like mMMLU and PIQA, and achieves state-of-the-art results in Thai.
To support low-resource language research, we release Xdata_Thai, a
Thai-specific evaluation dataset featuring unique linguistic challenges such as
gendered particles and idioms. While the model demonstrates strong performance,
there is still room for improvement in handling culturally specific nuances. We
hope this work contributes to advancements in multilingual AI research. Models
and code are publicly available on GitHub at
https://github.com/XiaoduoAILab/XmodelLM-1.5
