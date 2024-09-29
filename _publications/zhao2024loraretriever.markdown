---
layout: publication
title: LoraRetriever Input-Aware LoRA Retrieval and Composition for Mixed Tasks in the Wild
authors: Zhao Ziyu, Gan Leilei, Wang Guoyin, Zhou Wangchunshu, Yang Hongxia, Kuang Kun, Wu Fei
conference: "Arxiv"
year: 2024
bibkey: zhao2024loraretriever
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.09997"}
tags: ['Fine Tuning', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Low-Rank Adaptation (LoRA) provides an effective yet efficient solution for fine-tuning large language models (LLM). The modular and plug-and-play nature of LoRA enables the integration of diverse domain-specific LoRAs to enhance the capabilities of LLMs. Previous research on exploiting multiple LoRAs either focuses on specific isolated downstream tasks or fixes the selection of LoRAs during training. However in real-world scenarios LLMs receive diverse prompts covering different tasks and the pool of candidate LoRAs is often dynamically updated. To bridge this gap we propose LoraRetriever a retrieve-then-compose framework that adaptively retrieves and composes multiple LoRAs according to the input prompts. LoraRetriever contains three main components firstly identifying and retrieving LoRAs relevant to the given input; secondly formulating strategies for effectively integrating the retrieved LoRAs; and thirdly developing efficient batch inference to accommodate heterogeneous requests. Experimental results indicate that LoraRetriever consistently outperforms the baselines highlighting its practical effectiveness and versatility.
