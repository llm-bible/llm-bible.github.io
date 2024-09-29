---
layout: publication
title: What Language Model To Train If You Have One Million GPU Hours
authors: Scao Teven Le, Wang Thomas, Hesslow Daniel, Saulnier Lucile, Bekman Stas, Bari M Saiful, Biderman Stella, Elsahar Hady, Muennighoff Niklas, Phang Jason, Press Ofir, Raffel Colin, Sanh Victor, Shen Sheng, Sutawika Lintang, Tae Jaesung, Yong Zheng Xin, Launay Julien, Beltagy Iz
conference: "Arxiv"
year: 2022
bibkey: scao2022what
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2210.15424"}
  - {name: "Code", url: "https://huggingface.co/bigscience"}
tags: ['Has Code', 'Model Architecture', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
The crystallization of modeling methods around the Transformer architecture has been a boon for practitioners. Simple well-motivated architectural variations can transfer across tasks and scale increasing the impact of modeling research. However with the emergence of state-of-the-art 100B+ parameters models large language models are increasingly expensive to accurately design and train. Notably it can be difficult to evaluate how modeling decisions may impact emergent capabilities given that these capabilities arise mainly from sheer scale alone. In the process of building BLOOM--the Big Science Large Open-science Open-access Multilingual language model--our goal is to identify an architecture and training setup that makes the best use of our 1000000 A100-GPU-hours budget. Specifically we perform an ablation study at the billion-parameter scale comparing different modeling practices and their impact on zero-shot generalization. In addition we study the impact of various popular pre-training corpora on zero-shot generalization. We also study the performance of a multilingual model and how it compares to the English-only one. Finally we consider the scaling behaviour of Transformers to choose the target model size shape and training setup. All our models and code are open-sourced at https://huggingface.co/bigscience .
