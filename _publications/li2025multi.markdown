---
layout: publication
title: 'Multi-sourced Compositional Generalization In Visual Question Answering'
authors: Chuanhao Li, Wenbo Ye, Zhen Li, Yuwei Wu, Yunde Jia
conference: "Arxiv"
year: 2025
bibkey: li2025multi
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.23045"}
  - {name: "Code", url: "https://github.com/NeverMoreLCH/MSCG"}
tags: ['Training Techniques', 'Model Architecture', 'Tools', 'RAG', 'Has Code', 'Applications', 'Attention Mechanism']
---
Compositional generalization is the ability of generalizing novel compositions from seen primitives, and has received much attention in vision-and-language (V\&L) recently. Due to the multi-modal nature of V\&L tasks, the primitives composing compositions source from different modalities, resulting in multi-sourced novel compositions. However, the generalization ability over multi-sourced novel compositions, \textit\{i.e.\}, multi-sourced compositional generalization (MSCG) remains unexplored. In this paper, we explore MSCG in the context of visual question answering (VQA), and propose a retrieval-augmented training framework to enhance the MSCG ability of VQA models by learning unified representations for primitives from different modalities. Specifically, semantically equivalent primitives are retrieved for each primitive in the training samples, and the retrieved features are aggregated with the original primitive to refine the model. This process helps the model learn consistent representations for the same semantic primitives across different modalities. To evaluate the MSCG ability of VQA models, we construct a new GQA-MSCG dataset based on the GQA dataset, in which samples include three types of novel compositions composed of primitives from different modalities. Experimental results demonstrate the effectiveness of the proposed framework. We release GQA-MSCG at https://github.com/NeverMoreLCH/MSCG.
