---
layout: publication
title: Crayon Customized On-Device LLM via Instant Adapter Blending and Edge-Server Hybrid Inference
authors: Bang Jihwan, Lee Juntae, Shim Kyuhong, Yang Seunghan, Chang Simyung
conference: "Arxiv"
year: 2024
bibkey: bang2024crayon
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.07007"}
tags: ['Pretraining Methods', 'LLM', 'Arxiv']
---
The customization of large language models (LLMs) for user-specified tasks gets important. However maintaining all the customized LLMs on cloud servers incurs substantial memory and computational overheads and uploading user data can also lead to privacy concerns. On-device LLMs can offer a promising solution by mitigating these issues. Yet the performance of on-device LLMs is inherently constrained by the limitations of small-scaled models. To overcome these restrictions we first propose Crayon a novel approach for on-device LLM customization. Crayon begins by constructing a pool of diverse base adapters and then we instantly blend them into a customized adapter without extra training. In addition we develop a device-server hybrid inference strategy which deftly allocates more demanding queries or non-customized tasks to a larger more capable LLM on a server. This ensures optimal performance without sacrificing the benefits of on-device customization. We carefully craft a novel benchmark from multiple question-answer datasets and show the efficacy of our method in the LLM customization.
