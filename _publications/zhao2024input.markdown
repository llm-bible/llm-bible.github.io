---
layout: publication
title: Loraretriever Input45;aware Lora Retrieval And Composition For Mixed Tasks In The Wild
authors: Zhao Ziyu, Gan Leilei, Wang Guoyin, Zhou Wangchunshu, Yang Hongxia, Kuang Kun, Wu Fei
conference: "Arxiv"
year: 2024
bibkey: zhao2024input
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.09997"}
tags: ['Ethics And Bias', 'Fine Tuning', 'Prompting', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Low45;Rank Adaptation (LoRA) provides an effective yet efficient solution for fine45;tuning large language models (LLM). The modular and plug45;and45;play nature of LoRA enables the integration of diverse domain45;specific LoRAs to enhance the capabilities of LLMs. Previous research on exploiting multiple LoRAs either focuses on specific isolated downstream tasks or fixes the selection of LoRAs during training. However in real45;world scenarios LLMs receive diverse prompts covering different tasks and the pool of candidate LoRAs is often dynamically updated. To bridge this gap we propose LoraRetriever a retrieve45;then45;compose framework that adaptively retrieves and composes multiple LoRAs according to the input prompts. LoraRetriever contains three main components firstly identifying and retrieving LoRAs relevant to the given input; secondly formulating strategies for effectively integrating the retrieved LoRAs; and thirdly developing efficient batch inference to accommodate heterogeneous requests. Experimental results indicate that LoraRetriever consistently outperforms the baselines highlighting its practical effectiveness and versatility.
