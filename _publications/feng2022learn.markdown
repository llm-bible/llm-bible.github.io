---
layout: publication
title: 'Learn To Remember: Transformer With Recurrent Memory For Document-level Machine Translation'
authors: Feng Yukun, Li Feng, Song Ziang, Zheng Boyuan, Koehn Philipp
conference: "Findings of the Association for Computational Linguistics NAACL"
year: 2022
bibkey: feng2022learn
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2205.01546"}
tags: ['Applications', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
The Transformer architecture has led to significant gains in machine translation. However most studies focus on only sentence-level translation without considering the context dependency within documents leading to the inadequacy of document-level coherence. Some recent research tried to mitigate this issue by introducing an additional context encoder or translating with multiple sentences or even the entire document. Such methods may lose the information on the target side or have an increasing computational complexity as documents get longer. To address such problems we introduce a recurrent memory unit to the vanilla Transformer which supports the information exchange between the sentence and previous context. The memory unit is recurrently updated by acquiring information from sentences and passing the aggregated knowledge back to subsequent sentence states. We follow a two-stage training strategy in which the model is first trained at the sentence level and then finetuned for document-level translation. We conduct experiments on three popular datasets for document-level machine translation and our model has an average improvement of 0.91 s-BLEU over the sentence-level baseline. We also achieve state-of-the-art results on TED and News outperforming the previous work by 0.36 s-BLEU and 1.49 d-BLEU on average.
