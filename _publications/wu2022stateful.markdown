---
layout: publication
title: 'Stateful Memory-augmented Transformers For Efficient Dialogue Modeling'
authors: Wu Qingyang, Yu Zhou
conference: "Arxiv"
year: 2022
bibkey: wu2022stateful
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2209.07634"}
tags: ['Efficiency And Optimization', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'Transformer']
---
Transformer encoder-decoder models have achieved great performance in dialogue generation tasks however their inability to process long dialogue history often leads to truncation of the context To address this problem we propose a novel memory-augmented transformer that is compatible with existing pre-trained encoder-decoder models and enables efficient preservation of the dialogue history information. By incorporating a separate memory module alongside the pre-trained transformer the model can effectively interchange information between the memory states and the current input context. We evaluate our model on three dialogue datasets and two language modeling datasets. Experimental results show that our method has achieved superior efficiency and performance compared to other pre-trained Transformer baselines.
