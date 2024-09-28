---
layout: publication
title: Prior Knowledge Integration via LLM Encoding and Pseudo Event Regulation for Video Moment Retrieval
authors: Jiang Yiyang, Zhang Wengyu, Zhang Xulu, Wei Xiaoyong, Chen Chang Wen, Li Qing
conference: "Arxiv"
year: 2024
bibkey: jiang2024prior
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.15051"}
  - {name: "Code", url: "https://github.com/fletcherjiang/LLMEPET"}
tags: ['ARXIV', 'Applications', 'Has Code', 'LLM']
---
In this paper we investigate the feasibility of leveraging large language models (LLMs) for integrating general knowledge and incorporating pseudo-events as priors for temporal content distribution in video moment retrieval (VMR) models. The motivation behind this study arises from the limitations of using LLMs as decoders for generating discrete textual descriptions which hinders their direct application to continuous outputs like salience scores and inter-frame embeddings that capture inter-frame relations. To overcome these limitations we propose utilizing LLM encoders instead of decoders. Through a feasibility study we demonstrate that LLM encoders effectively refine inter-concept relations in multimodal embeddings even without being trained on textual embeddings. We also show that the refinement capability of LLM encoders can be transferred to other embeddings such as BLIP and T5 as long as these embeddings exhibit similar inter-concept similarity patterns to CLIP embeddings. We present a general framework for integrating LLM encoders into existing VMR architectures specifically within the fusion module. Through experimental validation we demonstrate the effectiveness of our proposed methods by achieving state-of-the-art performance in VMR. The source code can be accessed at https://github.com/fletcherjiang/LLMEPET.
