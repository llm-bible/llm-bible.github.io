---
layout: publication
title: 'Retrieval-augmented Mixture Of Lora Experts For Uploadable Machine Learning'
authors: Zhao Ziyu, Gan Leilei, Wang Guoyin, Hu Yuwei, Shen Tao, Yang Hongxia, Kuang Kun, Wu Fei
conference: "Arxiv"
year: 2024
bibkey: zhao2024retrieval
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.16989"}
tags: ['Fine Tuning', 'Prompting', 'RAG', 'Tools', 'Training Techniques']
---
Low-Rank Adaptation (LoRA) offers an efficient way to fine-tune large language models (LLMs). Its modular and plug-and-play nature allows the integration of various domain-specific LoRAs enhancing LLM capabilities. Open-source platforms like Huggingface and Modelscope have introduced a new computational paradigm Uploadable Machine Learning (UML). In UML contributors use decentralized data to train specialized adapters which are then uploaded to a central platform to improve LLMs. This platform uses these domain-specific adapters to handle mixed-task requests requiring personalized service. Previous research on LoRA composition either focuses on specific tasks or fixes the LoRA selection during training. However in UML the pool of LoRAs is dynamically updated with new uploads requiring a generalizable selection mechanism for unseen LoRAs. Additionally the mixed-task nature of downstream requests necessitates personalized services. To address these challenges we propose Retrieval-Augmented Mixture of LoRA Experts (RAMoLE) a framework that adaptively retrieves and composes multiple LoRAs based on input prompts. RAMoLE has three main components LoraRetriever for identifying and retrieving relevant LoRAs an on-the-fly MoLE mechanism for coordinating the retrieved LoRAs and efficient batch inference for handling heterogeneous requests. Experimental results show that RAMoLE consistently outperforms baselines highlighting its effectiveness and scalability.
