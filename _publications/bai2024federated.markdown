---
layout: publication
title: Federated Fine45;tuning Of Large Language Models Under Heterogeneous Tasks And Client Resources
authors: Bai Jiamu, Chen Daoyuan, Qian Bingchen, Yao Liuyi, Li Yaliang
conference: "Arxiv"
year: 2024
bibkey: bai2024federated
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.11505"}
tags: ['Fine Tuning', 'Multimodal Models', 'RAG']
---
Federated Learning (FL) has recently been applied to the parameter45;efficient fine45;tuning of Large Language Models (LLMs). While promising it raises significant challenges due to the heterogeneous resources and data distributions of clients. This study introduces FlexLoRA a simple yet effective aggregation scheme for LLM fine45;tuning which mitigates the bucket effect in traditional FL that restricts the potential of clients with ample resources by tying them to the capabilities of the least45;resourced participants. FlexLoRA allows for dynamic adjustment of local LoRA ranks fostering the development of a global model imbued with broader less task45;specific knowledge. By synthesizing a full45;size LoRA weight from individual client contributions and employing Singular Value Decomposition (SVD) for weight redistribution FlexLoRA fully leverages heterogeneous client resources. Involving thousands of clients performing heterogeneous NLP tasks and client resources our experiments validate the efficacy of FlexLoRA with the federated global model achieving consistently better improvement over SOTA FL methods in downstream NLP task performance across various heterogeneous distributions. FlexLoRAs practicality is further underscored by our theoretical analysis and its seamless integration with existing LoRA45;based FL methods offering a path toward cross45;device privacy45;preserving federated tuning for LLMs.
