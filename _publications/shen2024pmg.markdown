---
layout: publication
title: PMG &#58; Personalized Multimodal Generation With Large Language Models
authors: Shen Xiaoteng, Zhang Rui, Zhao Xiaoyan, Zhu Jieming, Xiao Xi
conference: "Arxiv"
year: 2024
bibkey: shen2024pmg
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.08677"}
tags: ['Applications', 'Attention Mechanism', 'Merging', 'Model Architecture', 'Multimodal Models', 'Prompting']
---
The emergence of large language models (LLMs) has revolutionized the capabilities of text comprehension and generation. Multi-modal generation attracts great attention from both the industry and academia but there is little work on personalized generation which has important applications such as recommender systems. This paper proposes the first method for personalized multimodal generation using LLMs showcases its applications and validates its performance via an extensive experimental study on two datasets. The proposed method Personalized Multimodal Generation (PMG for short) first converts user behaviors (e.g. clicks in recommender systems or conversations with a virtual assistant) into natural language to facilitate LLM understanding and extract user preference descriptions. Such user preferences are then fed into a generator such as a multimodal LLM or diffusion model to produce personalized content. To capture user preferences comprehensively and accurately we propose to let the LLM output a combination of explicit keywords and implicit embeddings to represent user preferences. Then the combination of keywords and embeddings are used as prompts to condition the generator. We optimize a weighted sum of the accuracy and preference scores so that the generated content has a good balance between them. Compared to a baseline method without personalization PMG has a significant improvement on personalization for up to 837; in terms of LPIPS while retaining the accuracy of generation.
