---
layout: publication
title: 'From Image To Video, What Do We Need In Multimodal Llms?'
authors: Suyuan Huang, Haoxin Zhang, Linqing Zhong, Honggu Chen, Yan Gao, Yao Hu, Zengchang Qin
conference: "Arxiv"
year: 2024
bibkey: huang2024from
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.11865"}
tags: ['Training Techniques', 'RAG', 'Pre-Training', 'Multimodal Models']
---
Covering from Image LLMs to the more complex Video LLMs, the Multimodal Large Language Models (MLLMs) have demonstrated profound capabilities in comprehending cross-modal information as numerous studies have illustrated. Previous methods delve into designing comprehensive Video LLMs through integrating video foundation models with primitive LLMs. Despite its effectiveness, such paradigm renders Video LLM's structure verbose and typically requires substantial video data for pre-training. Crucially, it neglects leveraging the foundational contributions of ready-made Image LLMs. In this paper, we introduce RED-VILLM, a Resource-Efficient Development pipeline which builds robust Video LLMs through leveraging the prior knowledge of Image LLMs. Specifically, since a video is naturally a combination of images along the temporal dimension, we devise a temporal adaptation plug-and-play structure, endowing the backbone Image LLM with the capability to grasp temporal information. Moreover, through applying this pipeline, we achieve the first Video LLM within the Chinese-speaking community. Extensive experiments demonstrate that Video LLMs developed through our approach surpass conventional Video LLMs, requiring minimal instructional data and training resources. Our approach highlights the potential for a more cost-effective and scalable advancement in multimodal models.
