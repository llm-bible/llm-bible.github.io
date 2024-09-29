---
layout: publication
title: Prior Knowledge Integration Via LLM Encoding And Pseudo Event Regulation For Video Moment Retrieval
authors: Jiang Yiyang, Zhang Wengyu, Zhang Xulu, Wei Xiaoyong, Chen Chang Wen, Li Qing
conference: "Arxiv"
year: 2024
bibkey: jiang2024prior
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.15051"}
  - {name: "Code", url: "https://github.com/fletcherjiang/LLMEPET"}
tags: ['Has Code', 'Merging', 'Model Architecture', 'Multimodal Models', 'RAG', 'Tools']
---
In this paper we investigate the feasibility of leveraging large language models (LLMs) for integrating general knowledge and incorporating pseudo45;events as priors for temporal content distribution in video moment retrieval (VMR) models. The motivation behind this study arises from the limitations of using LLMs as decoders for generating discrete textual descriptions which hinders their direct application to continuous outputs like salience scores and inter45;frame embeddings that capture inter45;frame relations. To overcome these limitations we propose utilizing LLM encoders instead of decoders. Through a feasibility study we demonstrate that LLM encoders effectively refine inter45;concept relations in multimodal embeddings even without being trained on textual embeddings. We also show that the refinement capability of LLM encoders can be transferred to other embeddings such as BLIP and T5 as long as these embeddings exhibit similar inter45;concept similarity patterns to CLIP embeddings. We present a general framework for integrating LLM encoders into existing VMR architectures specifically within the fusion module. Through experimental validation we demonstrate the effectiveness of our proposed methods by achieving state45;of45;the45;art performance in VMR. The source code can be accessed at https://github.com/fletcherjiang/LLMEPET.
