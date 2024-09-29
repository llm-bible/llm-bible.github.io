---
layout: publication
title: MGA45;VQA Multi45;granularity Alignment For Visual Question Answering
authors: Xiong Peixi, Shen Yilin, Jin Hongxia
conference: "Arxiv"
year: 2022
bibkey: xiong2022mga
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2201.10656"}
tags: ['Applications', 'Attention Mechanism', 'Merging', 'Model Architecture', 'Pretraining Methods', 'Training Techniques']
---
Learning to answer visual questions is a challenging task since the multi45;modal inputs are within two feature spaces. Moreover reasoning in visual question answering requires the model to understand both image and question and align them in the same space rather than simply memorize statistics about the question45;answer pairs. Thus it is essential to find component connections between different modalities and within each modality to achieve better attention. Previous works learned attention weights directly on the features. However the improvement is limited since these two modality features are in two domains image features are highly diverse lacking structure and grammatical rules as language and natural language features have a higher probability of missing detailed information. To better learn the attention between visual and text we focus on how to construct input stratification and embed structural information to improve the alignment between different level components. We propose Multi45;Granularity Alignment architecture for Visual Question Answering task (MGA45;VQA) which learns intra45; and inter45;modality correlations by multi45;granularity alignment and outputs the final result by the decision fusion module. In contrast to previous works our model splits alignment into different levels to achieve learning better correlations without needing additional data and annotations. The experiments on the VQA45;v2 and GQA datasets demonstrate that our model significantly outperforms non45;pretrained state45;of45;the45;art methods on both datasets without extra pretraining data and annotations. Moreover it even achieves better results over the pre45;trained methods on GQA.
