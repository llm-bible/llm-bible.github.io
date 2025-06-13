---
layout: publication
title: 'Lower Layers Matter: Alleviating Hallucination Via Multi-layer Fusion Contrastive Decoding With Truthfulness Refocused'
authors: Dingwei Chen, Feiteng Fang, Shiwen Ni, Feng Liang, Xiping Hu, Ahmadreza Argha, Hamid Alinejad-rokny, Min Yang, Chengming Li
conference: "Arxiv"
year: 2024
bibkey: chen2024lower
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.08769"}
tags: ['RAG', 'Tools', 'Merging']
---
Large Language Models (LLMs) have demonstrated exceptional performance across various natural language processing tasks. However, they occasionally generate inaccurate and counterfactual outputs, a phenomenon commonly referred to as "hallucinations''. To tackle this issue, recent studies have explored contrastive decoding between the original model and an amateur model with induced hallucination, showing promising results. Nevertheless, this approach can disrupt the original LLM's output distribution due to coarse contrast and simple subtraction operations, potentially leading to errors. In this paper, we introduce a novel contrastive decoding framework, termed LOL (LOwer Layer Matters). Unlike prior methods that focus solely on the final layer, our approach integrates contrastive information from lower layers to enable multi-layer fusion during contrastive decoding. Additionally, we incorporate a truthfulness refocused module that leverages instruction guidance to further improve truthfulness in contrastive decoding. Extensive experiments on four publicly available datasets demonstrate that the LOL framework significantly mitigates hallucination while outperforming existing baselines in most cases. For reproducibility, we will release our code and data upon acceptance.
