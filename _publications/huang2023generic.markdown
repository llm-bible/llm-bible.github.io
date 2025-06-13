---
layout: publication
title: 'Generic Attention-model Explainability By Weighted Relevance Accumulation'
authors: Yiming Huang, Aozhe Jia, Xiaodan Zhang, Jiawei Zhang
conference: "Arxiv"
year: 2023
bibkey: huang2023generic
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2308.10240'}
tags: ['Attention Mechanism', 'Interpretability and Explainability', 'Transformer', 'Model Architecture', 'Applications', 'Multimodal Models', 'Interpretability', 'Pretraining Methods']
---
Attention-based transformer models have achieved remarkable progress in
multi-modal tasks, such as visual question answering. The explainability of
attention-based methods has recently attracted wide interest as it can explain
the inner changes of attention tokens by accumulating relevancy across
attention layers. Current methods simply update relevancy by equally
accumulating the token relevancy before and after the attention processes.
However, the importance of token values is usually different during relevance
accumulation. In this paper, we propose a weighted relevancy strategy, which
takes the importance of token values into consideration, to reduce distortion
when equally accumulating relevance. To evaluate our method, we propose a
unified CLIP-based two-stage model, named CLIPmapper, to process
Vision-and-Language tasks through CLIP encoder and a following mapper.
CLIPmapper consists of self-attention, cross-attention, single-modality, and
cross-modality attention, thus it is more suitable for evaluating our generic
explainability method. Extensive perturbation tests on visual question
answering and image captioning validate that our explainability method
outperforms existing methods.
