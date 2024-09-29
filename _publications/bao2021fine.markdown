---
layout: publication
title: S2s45;ft Fine45;tuning Pretrained Transformer Encoders For Sequence45;to45;sequence Learning
authors: Bao Hangbo, Dong Li, Wang Wenhui, Yang Nan, Wei Furu
conference: "Arxiv"
year: 2021
bibkey: bao2021fine
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2110.13640"}
  - {name: "Code", url: "https://github.com/microsoft/unilm/tree/master/s2s&#45;ft"}
tags: ['Applications', 'BERT', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Transformer']
---
Pretrained bidirectional Transformers such as BERT have achieved significant improvements in a wide variety of language understanding tasks while it is not straightforward to directly apply them for natural language generation. In this paper we present a sequence45;to45;sequence fine45;tuning toolkit s2s45;ft which adopts pretrained Transformers for conditional generation tasks. Inspired by UniLM we implement three sequence45;to45;sequence fine45;tuning algorithms namely causal fine45;tuning masked fine45;tuning and pseudo45;masked fine45;tuning. By leveraging the existing pretrained bidirectional Transformers experimental results show that s2s45;ft achieves strong performance on several benchmarks of abstractive summarization and question generation. Moreover we demonstrate that the package s2s45;ft supports both monolingual and multilingual NLG tasks. The s2s45;ft toolkit is available at https://github.com/microsoft/unilm/tree/master/s2s&#45;ft.
