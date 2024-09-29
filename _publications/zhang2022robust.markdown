---
layout: publication
title: BLISS Robust Sequence45;to45;sequence Learning Via Self45;supervised Input Representation
authors: Zhang Zheng, Ding Liang, Cheng Dazhao, Liu Xuebo, Zhang Min, Tao Dacheng
conference: "Arxiv"
year: 2022
bibkey: zhang2022robust
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2204.07837"}
tags: ['Applications', 'Model Architecture', 'Pretraining Methods', 'Tools', 'Transformer']
---
Data augmentations (DA) are the cores to achieving robust sequence45;to45;sequence learning on various natural language processing (NLP) tasks. However most of the DA approaches force the decoder to make predictions conditioned on the perturbed input representation underutilizing supervised information provided by perturbed input. In this work we propose a framework45;level robust sequence45;to45;sequence learning approach named BLISS via self45;supervised input representation which has the great potential to complement the data45;level augmentation approaches. The key idea is to supervise the sequence45;to45;sequence framework with both the textit123;supervised125; (input→output) and textit123;self45;supervised125; (perturbed input→input) information. We conduct comprehensive experiments to validate the effectiveness of BLISS on various tasks including machine translation grammatical error correction and text summarization. The results show that BLISS outperforms significantly the vanilla Transformer and consistently works well across tasks than the other five contrastive baselines. Extensive analyses reveal that BLISS learns robust representations and rich linguistic knowledge confirming our claim. Source code will be released upon publication.
