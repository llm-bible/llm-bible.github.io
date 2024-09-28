---
layout: publication
title: CuMo Scaling Multimodal LLM with Co-Upcycled Mixture-of-Experts
authors: Li Jiachen, Wang Xinyao, Zhu Sijie, Kuo Chia-wen, Xu Lu, Chen Fan, Jain Jitesh, Shi Humphrey, Wen Longyin
conference: "Arxiv"
year: 2024
bibkey: li2024cumo
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.05949"}
  - {name: "Code", url: "https://github.com/SHI-Labs/CuMo"}
tags: ['ARXIV', 'Applications', 'Has Code', 'LLM', 'Multimodal Models', 'Reinforcement Learning']
---
Recent advancements in Multimodal Large Language Models (LLMs) have focused primarily on scaling by increasing text-image pair data and enhancing LLMs to improve performance on multimodal tasks. However these scaling approaches are computationally expensive and overlook the significance of improving model capabilities from the vision side. Inspired by the successful applications of Mixture-of-Experts (MoE) in LLMs which improves model scalability during training while keeping inference costs similar to those of smaller models we propose CuMo. CuMo incorporates Co-upcycled Top-K sparsely-gated Mixture-of-experts blocks into both the vision encoder and the MLP connector thereby enhancing the multimodal LLMs with minimal additional activated parameters during inference. CuMo first pre-trains the MLP blocks and then initializes each expert in the MoE block from the pre-trained MLP block during the visual instruction tuning stage. Auxiliary losses are used to ensure a balanced loading of experts. CuMo outperforms state-of-the-art multimodal LLMs across various VQA and visual-instruction-following benchmarks using models within each model size group all while training exclusively on open-sourced datasets. The code and model weights for CuMo are open-sourced at https://github.com/SHI-Labs/CuMo.
