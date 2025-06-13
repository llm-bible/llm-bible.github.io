---
layout: publication
title: 'S2s-ft: Fine-tuning Pretrained Transformer Encoders For Sequence-to-sequence Learning'
authors: Hangbo Bao, Li Dong, Wenhui Wang, Nan Yang, Furu Wei
conference: "Arxiv"
year: 2021
bibkey: bao2021fine
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2110.13640'}
  - {name: "Code", url: 'https://github.com/microsoft/unilm/tree/master/s2s-ft'}
tags: ['Has Code', 'Transformer', 'RAG', 'Training Techniques', 'BERT', 'Model Architecture', 'Fine-Tuning', 'Applications', 'Reinforcement Learning', 'Pretraining Methods']
---
Pretrained bidirectional Transformers, such as BERT, have achieved
significant improvements in a wide variety of language understanding tasks,
while it is not straightforward to directly apply them for natural language
generation. In this paper, we present a sequence-to-sequence fine-tuning
toolkit s2s-ft, which adopts pretrained Transformers for conditional generation
tasks. Inspired by UniLM, we implement three sequence-to-sequence fine-tuning
algorithms, namely, causal fine-tuning, masked fine-tuning, and pseudo-masked
fine-tuning. By leveraging the existing pretrained bidirectional Transformers,
experimental results show that s2s-ft achieves strong performance on several
benchmarks of abstractive summarization, and question generation. Moreover, we
demonstrate that the package s2s-ft supports both monolingual and multilingual
NLG tasks. The s2s-ft toolkit is available at
https://github.com/microsoft/unilm/tree/master/s2s-ft.
