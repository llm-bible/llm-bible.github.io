---
layout: publication
title: 'Xdoc: Unified Pre-training For Cross-format Document Understanding'
authors: Jingye Chen, Tengchao Lv, Lei Cui, Cha Zhang, Furu Wei
conference: "Arxiv"
year: 2022
bibkey: chen2022unified
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2210.02849"}
  - {name: "Code", url: "https://aka.ms/xdoc"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'Pretraining Methods', 'Fine-Tuning', 'Transformer', 'Has Code', 'Pre-Training']
---
The surge of pre-training has witnessed the rapid development of document
understanding recently. Pre-training and fine-tuning framework has been
effectively used to tackle texts in various formats, including plain texts,
document texts, and web texts. Despite achieving promising performance,
existing pre-trained models usually target one specific document format at one
time, making it difficult to combine knowledge from multiple document formats.
To address this, we propose XDoc, a unified pre-trained model which deals with
different document formats in a single model. For parameter efficiency, we
share backbone parameters for different formats such as the word embedding
layer and the Transformer layers. Meanwhile, we introduce adaptive layers with
lightweight parameters to enhance the distinction across different formats.
Experimental results have demonstrated that with only 36.7% parameters, XDoc
achieves comparable or even better performance on a variety of downstream tasks
compared with the individual pre-trained models, which is cost effective for
real-world deployment. The code and pre-trained models will be publicly
available at \url\{https://aka.ms/xdoc\}.
