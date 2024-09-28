---
layout: publication
title: Cost-Effective Hallucination Detection for LLMs
authors: Valentin Simon, Fu Jinmiao, Detommaso Gianluca, Xu Shaoyuan, Zappella Giovanni, Wang Bryan
conference: "Arxiv"
year: 2024
bibkey: valentin2024cost
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.21424"}
tags: ['Applications', 'Arxiv']
---
Large language models (LLMs) can be prone to hallucinations - generating unreliable outputs that are unfaithful to their inputs external facts or internally inconsistent. In this work we address several challenges for post-hoc hallucination detection in production settings. Our pipeline for hallucination detection entails first producing a confidence score representing the likelihood that a generated answer is a hallucination; second calibrating the score conditional on attributes of the inputs and candidate response; finally performing detection by thresholding the calibrated score. We benchmark a variety of state-of-the-art scoring methods on different datasets encompassing question answering fact checking and summarization tasks. We employ diverse LLMs to ensure a comprehensive assessment of performance. We show that calibrating individual scoring methods is critical for ensuring risk-aware downstream decision making. Based on findings that no individual score performs best in all situations we propose a multi-scoring framework which combines different scores and achieves top performance across all datasets. We further introduce cost-effective multi-scoring which can match or even outperform more expensive detection methods while significantly reducing computational overhead.
