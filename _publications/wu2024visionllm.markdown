---
layout: publication
title: Visionllm V2 An End-to-end Generalist Multimodal Large Language Model For Hundreds Of Vision-language Tasks
authors: Wu Jiannan, Zhong Muyan, Xing Sen, Lai Zeqiang, Liu Zhaoyang, Wang Wenhai, Chen Zhe, Zhu Xizhou, Lu Lewei, Lu Tong, Luo Ping, Qiao Yu, Dai Jifeng
conference: "Arxiv"
year: 2024
bibkey: wu2024visionllm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.08394"}
tags: ['Applications', 'Multimodal Models', 'Prompting', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
We present VisionLLM v2 an end-to-end generalist multimodal large model (MLLM) that unifies visual perception understanding and generation within a single framework. Unlike traditional MLLMs limited to text output VisionLLM v2 significantly broadens its application scope. It excels not only in conventional visual question answering (VQA) but also in open-ended cross-domain vision tasks such as object localization pose estimation and image generation and editing. To this end we propose a new information transmission mechanism termed super link as a medium to connect MLLM with task-specific decoders. It not only allows flexible transmission of task information and gradient feedback between the MLLM and multiple downstream decoders but also effectively resolves training conflicts in multi-tasking scenarios. In addition to support the diverse range of tasks we carefully collected and combed training data from hundreds of public vision and vision-language tasks. In this way our model can be joint-trained end-to-end on hundreds of vision language tasks and generalize to these tasks using a set of shared parameters through different user prompts achieving performance comparable to task-specific models. We believe VisionLLM v2 will offer a new perspective on the generalization of MLLMs.
