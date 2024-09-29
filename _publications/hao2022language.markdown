---
layout: publication
title: Language Models Are General45;purpose Interfaces
authors: Yaru Hao, Haoyu Song, Li Dong, Shaohan Huang, Zewen Chi, Wenhui Wang, Shuming Ma, Furu Wei
conference: "Arxiv"
year: 2022
bibkey: hao2022language
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/http://arxiv.org/abs/2206.06336v1"}
tags: ['Applications', 'Attention Mechanism', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning']
---
Foundation models have received much attention due to their effectiveness across a broad range of downstream applications. Though there is a big convergence in terms of architecture most pretrained models are typically still developed for specific tasks or modalities. In this work we propose to use language models as a general45;purpose interface to various foundation models. A collection of pretrained encoders perceive diverse modalities (such as vision and language) and they dock with a language model that plays the role of a universal task layer. We propose a semi45;causal language modeling objective to jointly pretrain the interface and the modular encoders. We subsume the advantages and capabilities from both causal and non45;causal modeling thereby combining the best of two worlds. Specifically the proposed method not only inherits the capabilities of in45;context learning and open45;ended generation from causal language modeling but also is conducive to finetuning because of the bidirectional encoders. More importantly our approach seamlessly unlocks the combinations of the above capabilities e.g. enabling in45;context learning or instruction following with finetuned encoders. Experimental results across various language45;only and vision45;language benchmarks show that our model outperforms or is competitive with specialized models on finetuning zero45;shot generalization and few45;shot learning.
