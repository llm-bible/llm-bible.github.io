---
layout: publication
title: 'Root Defence Strategies: Ensuring Safety Of LLM At The Decoding Level'
authors: Xinyi Zeng, Yuying Shang, Jiawei Chen, Jingyuan Zhang, Yu Tian
conference: "Arxiv"
year: 2024
bibkey: zeng2024root
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.06809"}
tags: ['Responsible AI', 'Security', 'Model Architecture', 'RAG', 'Prompting']
---
Large language models (LLMs) have demonstrated immense utility across various
industries. However, as LLMs advance, the risk of harmful outputs increases due
to incorrect or malicious instruction prompts. While current methods
effectively address jailbreak risks, they share common limitations: 1) Judging
harmful responses from the prefill-level lacks utilization of the model's
decoding outputs, leading to relatively lower effectiveness and robustness. 2)
Rejecting potentially harmful responses based on a single evaluation can
significantly impair the model's helpfulness.This paper examines the LLMs'
capability to recognize harmful outputs, revealing and quantifying their
proficiency in assessing the danger of previous tokens. Motivated by pilot
experiment results, we design a robust defense mechanism at the decoding level.
Our novel decoder-oriented, step-by-step defense architecture corrects harmful
queries directly rather than rejecting them outright. We introduce speculative
decoding to enhance usability and facilitate deployment to boost secure
decoding speed. Extensive experiments demonstrate that our approach improves
model security without compromising reasoning speed. Notably, our method
leverages the model's ability to discern hazardous information, maintaining its
helpfulness compared to existing methods.
