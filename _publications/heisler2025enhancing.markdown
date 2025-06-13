---
layout: publication
title: 'Enhancing Learned Knowledge In Lora Adapters Through Efficient Contrastive Decoding On Ascend Npus'
authors: Morgan Lindsay Heisler, Linzi Xing, Ge Shi, Hanieh Sadri, Gursimran Singh, Weiwei Zhang, Tao Ye, Ying Xiong, Yong Zhang, Zhenan Fan
conference: "Arxiv"
year: 2025
bibkey: heisler2025enhancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.14620"}
tags: ['Ethics and Bias', 'RAG', 'Fine-Tuning', 'Tools']
---
Huawei Cloud users leverage LoRA (Low-Rank Adaptation) as an efficient and scalable method to fine-tune and customize large language models (LLMs) for application-specific needs. However, tasks that require complex reasoning or deep contextual understanding are often hindered by biases or interference from the base model when using typical decoding methods like greedy or beam search. These biases can lead to generic or task-agnostic responses from the base model instead of leveraging the LoRA-specific adaptations. In this paper, we introduce Contrastive LoRA Decoding (CoLD), a novel decoding framework designed to maximize the use of task-specific knowledge in LoRA-adapted models, resulting in better downstream performance. CoLD uses contrastive decoding by scoring candidate tokens based on the divergence between the probability distributions of a LoRA-adapted expert model and the corresponding base model. This approach prioritizes tokens that better align with the LoRA's learned representations, enhancing performance for specialized tasks. While effective, a naive implementation of CoLD is computationally expensive because each decoding step requires evaluating multiple token candidates across both models. To address this, we developed an optimized kernel for Huawei's Ascend NPU. CoLD achieves up to a 5.54% increase in task accuracy while reducing end-to-end latency by 28% compared to greedy decoding. This work provides practical and efficient decoding strategies for fine-tuned LLMs in resource-constrained environments and has broad implications for applied data science in both cloud and on-premises settings.
