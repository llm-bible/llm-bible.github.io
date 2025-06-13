---
layout: publication
title: 'Alphalora: Assigning Lora Experts Based On Layer Training Quality'
authors: Peijun Qing, Chongyang Gao, Yefan Zhou, Xingjian Diao, Yaoqing Yang, Soroush Vosoughi
conference: "Arxiv"
year: 2024
bibkey: qing2024assigning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.10054"}
  - {name: "Code", url: "https://github.com/morelife2017/alphalora"}
tags: ['Fine-Tuning', 'Efficiency and Optimization', 'RAG', 'Model Architecture', 'Training Techniques', 'Has Code', 'Pretraining Methods']
---
Parameter-efficient fine-tuning methods, such as Low-Rank Adaptation (LoRA),
are known to enhance training efficiency in Large Language Models (LLMs). Due
to the limited parameters of LoRA, recent studies seek to combine LoRA with
Mixture-of-Experts (MoE) to boost performance across various tasks. However,
inspired by the observed redundancy in traditional MoE structures, previous
studies identify similar redundancy among LoRA experts within the MoE
architecture, highlighting the necessity for non-uniform allocation of LoRA
experts across different layers. In this paper, we leverage Heavy-Tailed
Self-Regularization (HT-SR) Theory to design a fine-grained allocation
strategy. Our analysis reveals that the number of experts per layer correlates
with layer training quality, which exhibits significant variability across
layers. Based on this, we introduce AlphaLoRA, a theoretically principled and
training-free method for allocating LoRA experts to further mitigate
redundancy. Experiments on three models across ten language processing and
reasoning benchmarks demonstrate that AlphaLoRA achieves comparable or superior
performance over all baselines. Our code is available at
https://github.com/morelife2017/alphalora.
