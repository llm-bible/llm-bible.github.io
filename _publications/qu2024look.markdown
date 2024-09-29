---
layout: publication
title: Look Compare Decide Alleviating Hallucination in Large Vision-Language Models via Multi-View Multi-Path Reasoning
authors: Qu Xiaoye, Sun Jiashuo, Wei Wei, Cheng Yu
conference: "Arxiv"
year: 2024
bibkey: qu2024look
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.17150"}
tags: ['Multimodal Models', 'Tools', 'Training Techniques']
---
Recently Large Vision-Language Models (LVLMs) have demonstrated impressive capabilities in multi-modal context comprehension. However they still suffer from hallucination problems referring to generating inconsistent outputs with the image content. To mitigate hallucinations previous studies mainly focus on retraining LVLMs with custom datasets. Although effective they inherently come with additional computational costs. In this paper we propose a training-free framework that aims to reduce hallucinations by making the most of the innate capabilities of the LVLMs via ulti-iew Multi-ath Reasoning. Specifically we first devise a multi-view information-seeking strategy to thoroughly perceive the comprehensive information in the image which enriches the general global information captured by the original vision encoder in LVLMs. Furthermore during the answer decoding we observe that the occurrence of hallucinations has a strong correlation with the certainty of the answer tokens. Thus we propose multi-path reasoning for each information view to quantify and aggregate the certainty scores for each potential answer among multiple decoding paths and finally decide the output answer. By fully grasping the information in the image and carefully considering the certainty of the potential answers when decoding our MVP can effectively reduce hallucinations in LVLMs.The extensive experiments verify that our proposed MVP significantly mitigates the hallucination problem across four well-known LVLMs. The source code is available at .
