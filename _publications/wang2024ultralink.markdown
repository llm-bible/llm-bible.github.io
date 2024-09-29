---
layout: publication
title: Ultralink An Open-source Knowledge-enhanced Multilingual Supervised Fine-tuning Dataset
authors: Wang Haoyu, Wang Shuo, Yan Yukun, Wang Xujia, Yang Zhiyu, Xu Yuzhuang, Liu Zhenghao, Yang Liner, Ding Ning, Han Xu, Liu Zhiyuan, Sun Maosong
conference: "Arxiv"
year: 2024
bibkey: wang2024ultralink
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.04588"}
tags: ['Fine Tuning', 'Pretraining Methods', 'Training Techniques']
---
Open-source large language models (LLMs) have gained significant strength across diverse fields. Nevertheless the majority of studies primarily concentrate on English with only limited exploration into the realm of multilingual abilities. In this work we therefore construct an open-source multilingual supervised fine-tuning dataset. Different from previous works that simply translate English instructions we consider both the language-specific and language-agnostic abilities of LLMs. Firstly we introduce a knowledge-grounded data augmentation approach to elicit more language-specific knowledge of LLMs improving their ability to serve users from different countries. Moreover we find modern LLMs possess strong cross-lingual transfer capabilities thus repeatedly learning identical content in various languages is not necessary. Consequently we can substantially prune the language-agnostic supervised fine-tuning (SFT) data without any performance degradation making multilingual SFT more efficient. The resulting UltraLink dataset comprises approximately 1 million samples across five languages (i.e. En Zh Ru Fr Es) and the proposed data construction method can be easily extended to other languages. UltraLink-LM which is trained on UltraLink outperforms several representative baselines across many tasks.
