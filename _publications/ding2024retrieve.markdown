---
layout: publication
title: 'Retrieve Only When It Needs: Adaptive Retrieval Augmentation For Hallucination Mitigation In Large Language Models'
authors: Ding Hanxing, Pang Liang, Wei Zihao, Shen Huawei, Cheng Xueqi
conference: "Arxiv"
year: 2024
bibkey: ding2024retrieve
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.10612"}
tags: []
---
Hallucinations pose a significant challenge for the practical implementation
of large language models (LLMs). The utilization of parametric knowledge in
generating factual content is constrained by the limited knowledge of LLMs,
potentially resulting in internal hallucinations. While incorporating external
information can help fill knowledge gaps, it also introduces the risk of
irrelevant information, thereby increasing the likelihood of external
hallucinations. A careful and balanced integration of the parametric knowledge
within LLMs with external information is crucial to alleviate hallucinations.
In this study, we present Rowen, a novel approach that enhances LLMs with a
selective retrieval augmentation process tailored to address hallucinated
outputs. This process is governed by a multilingual semantic-aware detection
module, which evaluates the consistency of the perturbed responses across
various languages for the same queries. Upon detecting inconsistencies
indicative of hallucinations, Rowen activates the retrieval of external
information to rectify the model outputs. Rowen adeptly harmonizes the
intrinsic parameters in LLMs with external knowledge sources, effectively
mitigating hallucinations by ensuring a balanced integration of internal
reasoning and external evidence. Through a comprehensive empirical analysis, we
demonstrate that Rowen surpasses the current state-of-the-art in both detecting
and mitigating hallucinated content within the outputs of LLMs.
