---
layout: publication
title: Mulzdg: Multilingual Code-switching Framework For Zero-shot Dialogue Generation
authors: Liu Yongkang, Feng Shi, Wang Daling, Zhang Yifei
conference: "Arxiv"
year: 2022
bibkey: liu2022multilingual
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2208.08629"}
tags: ['GPT', 'Large Scale Training', 'Model Architecture', 'Tools', 'Training Techniques']
---
Building dialogue generation systems in a zero-shot scenario remains a huge challenge since the typical zero-shot approaches in dialogue generation rely heavily on large-scale pre-trained language generation models such as GPT-3 and T5. The research on zero-shot dialogue generation without cumbersome language models is limited due to lacking corresponding parallel dialogue corpora. In this paper we propose a simple but effective Multilingual learning framework for Zero-shot Dialogue Generation (dubbed as MulZDG) that can effectively transfer knowledge from an English corpus with large-scale training samples to a non-English corpus with zero samples. Besides MulZDG can be viewed as a multilingual data augmentation method to improve the performance of the resource-rich language. First we construct multilingual code-switching dialogue datasets via translation utterances randomly selected from monolingual English datasets. Then we employ MulZDG to train a unified multilingual dialogue model based on the code-switching datasets. The MulZDG can conduct implicit semantic alignment between different languages. Experiments on DailyDialog and DSTC7 datasets demonstrate that MulZDG not only achieve competitive performance under zero-shot case compared to training with sufficient examples but also greatly improve the performance of the source language.
