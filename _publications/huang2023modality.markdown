---
layout: publication
title: Modality Plug-and-Play Elastic Modality Adaptation in Multimodal LLMs for Embodied AI
authors: Huang Kai, Yang Boyuan, Gao Wei
conference: "Arxiv"
year: 2023
bibkey: huang2023modality
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.07886"}
tags: ['ARXIV', 'Applications', 'LLM', 'Multimodal Models']
---
Large Language Models (LLMs) are capable of reasoning over diverse input data modalities through pre-trained encoders. However the growing diversity of input data modalities prevents incorporating all modalities into LLMs especially when LLMs are deployed on resource-constrained edge devices for embodied AI applications. Instead a better option is to adaptively involve only the useful modalities at runtime depending on the current environmental contexts and task requirements. For such modality adaptation existing work adopts fixed connections between encoders and the LLMs input layer leading to high training cost at runtime and ineffective cross-modal interaction. In this paper we address these limitations by presenting mPnP-LLM a new technique that allows fully elastic automated and prompt runtime modality adaptation by connecting unimodal encoders to a flexible set of last LLM blocks and making such latent connections fully trainable at runtime. Experiments over the nuScenes-QA dataset show that mPnP-LLM can achieve up to 3.7x FLOPs reduction and 30 GPU memory usage reduction while retaining on-par accuracy with the existing schemes. Under the same compute budget mPnP-LLM improves the task accuracy by up to 4 compared to the best existing scheme.
