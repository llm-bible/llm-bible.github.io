---
layout: publication
title: Contrastive Vision45;language Alignment Makes Efficient Instruction Learner
authors: Liu Lizhao, Sun Xinyu, Xiang Tianhang, Zhuang Zhuangwei, Yin Liuren, Tan Mingkui
conference: "Arxiv"
year: 2023
bibkey: liu2023contrastive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.17945"}
tags: ['Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'RAG', 'Transformer']
---
We study the task of extending the large language model (LLM) into a vision45;language instruction45;following model. This task is crucial but challenging since the LLM is trained on text modality only making it hard to effectively digest the visual modality. To address this existing methods typically train a visual adapter to align the representation between a pre45;trained vision transformer (ViT) and the LLM by a generative image captioning loss. However we find that the generative objective can only produce weak alignment for vision and language making the aligned vision45;language model very hungry for the instruction fine45;tuning data. In this paper we propose CG45;VLM that applies both Contrastive and Generative alignment objectives to effectively align the representation of ViT and LLM. Different from image level and sentence level alignment in common contrastive learning settings CG45;VLM aligns the image45;patch level features and text45;token level embeddings which however is very hard to achieve as no explicit grounding patch45;token relation provided in standard image captioning datasets. To address this issue we propose to maximize the averaged similarity between pooled image45;patch features and text45;token embeddings. Extensive experiments demonstrate that the proposed CG45;VLM produces strong vision45;language alignment and is an efficient instruction learner. For example using only 1037; instruction tuning data we reach 9537; performance of state45;of45;the45;art method LLaVA 29 on the zero45;shot ScienceQA45;Image benchmark.
