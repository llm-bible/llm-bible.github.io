---
layout: publication
title: Action Controlled Paraphrasing
authors: Shi Ning, Wu Zijun
conference: "Arxiv"
year: 2024
bibkey: shi2024action
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.11277"}
tags: ['Applications', 'Attention Mechanism', 'Merging', 'Model Architecture', 'Multimodal Models', 'RAG', 'Training Techniques']
---
Recent studies have demonstrated the potential to control paraphrase generation such as through syntax which has broad applications in various downstream tasks. However these methods often require detailed parse trees or syntactic exemplars countering human45;like paraphrasing behavior in language use. Furthermore an inference gap exists as control specifications are only available during training but not during inference. In this work we propose a new setup for controlled paraphrase generation. Specifically we represent user intent as action tokens embedding and concatenating them with text embeddings thus flowing together into a self45;attention encoder for representation fusion. To address the inference gap we introduce an optional action token as a placeholder that encourages the model to determine the appropriate action independently when users intended actions are not provided. Experimental results show that our method successfully enables precise action45;controlled paraphrasing and preserves or even enhances performance compared to conventional uncontrolled methods when actions are not given. Our findings promote the concept of action45;controlled paraphrasing for a more user45;centered design.
