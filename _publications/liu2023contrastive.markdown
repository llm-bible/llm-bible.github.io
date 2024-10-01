---
layout: publication
title: 'Contrastive Vision-language Alignment Makes Efficient Instruction Learner'
authors: Liu Lizhao, Sun Xinyu, Xiang Tianhang, Zhuang Zhuangwei, Yin Liuren, Tan Mingkui
conference: "Arxiv"
year: 2023
bibkey: liu2023contrastive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.17945"}
tags: ['Fine Tuning', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'RAG', 'Training Techniques', 'Transformer']
---
'We study the task of extending the large language model (LLM) into a vision-language instruction-following model. This task is crucial but challenging since the LLM is trained on text modality only, making it hard to effectively digest the visual modality. To address this, existing methods typically train a visual adapter to align the representation between a pre-trained vision transformer (ViT) and the LLM by a generative image captioning loss. However, we find that the generative objective can only produce weak alignment for vision and language, making the aligned vision-language model very hungry for the instruction fine-tuning data. In this paper, we propose CG-VLM that applies both Contrastive and Generative alignment objectives to effectively align the representation of ViT and LLM. Different from image level and sentence level alignment in common contrastive learning settings, CG-VLM aligns the image-patch level features and text-token level embeddings, which, however, is very hard to achieve as no explicit grounding patch-token relation provided in standard image captioning datasets. To address this issue, we propose to maximize the averaged similarity between pooled image-patch features and text-token embeddings. Extensive experiments demonstrate that the proposed CG-VLM produces strong vision-language alignment and is an efficient instruction learner. For example, using only 10&#37; instruction tuning data, we reach 95&#37; performance of state-of-the-art method LLaVA [29] on the zero-shot ScienceQA-Image benchmark.'
