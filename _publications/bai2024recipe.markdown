---
layout: publication
title: Longalign A Recipe For Long Context Alignment Of Large Language Models
authors: Bai Yushi, Lv Xin, Zhang Jiajie, He Yuze, Qi Ji, Hou Lei, Tang Jie, Dong Yuxiao, Li Juanzi
conference: "Arxiv"
year: 2024
bibkey: bai2024recipe
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.18058"}
  - {name: "Code", url: "https://github.com/THUDM/LongAlign"}
tags: ['Has Code', 'Pretraining Methods', 'Training Techniques']
---
Extending large language models to effectively handle long contexts requires instruction fine45;tuning on input sequences of similar length. To address this we present LongAlign 45;45; a recipe of the instruction data training and evaluation for long context alignment. First we construct a long instruction45;following dataset using Self45;Instruct. To ensure the data diversity it covers a broad range of tasks from various long context sources. Second we adopt the packing and sorted batching strategies to speed up supervised fine45;tuning on data with varied length distributions. Additionally we develop a loss weighting method to balance the contribution to the loss across different sequences during packing training. Third we introduce the LongBench45;Chat benchmark for evaluating instruction45;following capabilities on queries of 10k45;100k in length. Experiments show that LongAlign outperforms existing recipes for LLMs in long context tasks by up to 3037; while also maintaining their proficiency in handling short generic tasks. The code data and long45;aligned models are open45;sourced at https://github.com/THUDM/LongAlign.
