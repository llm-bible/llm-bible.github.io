---
layout: publication
title: 'Harmonized Speculative Sampling'
authors: Zhang Lefan, Wang Xiaodan, Huang Yanhua, Xu Ruiwen
conference: "Arxiv"
year: 2024
bibkey: zhang2024harmonized
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.15766"}
tags: ['Attention Mechanism', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Training Techniques']
---
Speculative sampling has proven to be an effective solution to accelerate decoding from large language models where the acceptance rate significantly determines the performance. Most previous works on improving the acceptance rate focus on aligned training and efficient decoding implicitly paying less attention to the linkage of training and decoding. In this work we first investigate the linkage of training and decoding for speculative sampling and then propose a solution named HArmonized Speculative Sampling (HASS). HASS improves the acceptance rate without extra inference overhead by harmonizing training and decoding on their objectives and contexts. Experiments on three LLaMA models demonstrate that HASS achieves 2.81x-3.65x wall-clock time speedup ratio averaging across three datasets which is 837;-1537; faster than EAGLE-2.
