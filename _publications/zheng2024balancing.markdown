---
layout: publication
title: Balancing Enhancement, Harmlessness, And General Capabilities: Enhancing Conversational Llms With Direct RLHF
authors: Zheng Chen, Sun Ke, Wu Hang, Xi Chenguang, Zhou Xun
conference: "Arxiv"
year: 2024
bibkey: zheng2024balancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.02513"}
tags: ['Agentic', 'Fine Tuning', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning', 'Responsible AI', 'Training Techniques']
---
In recent advancements in Conversational Large Language Models (LLMs) a concerning trend has emerged showing that many new base LLMs experience a knowledge reduction in their foundational capabilities following Supervised Fine-Tuning (SFT). This process often leads to issues such as forgetting or a decrease in the base models abilities. Moreover fine-tuned models struggle to align with user preferences inadvertently increasing the generation of toxic outputs when specifically prompted. To overcome these challenges we adopted an innovative approach by completely bypassing SFT and directly implementing Harmless Reinforcement Learning from Human Feedback (RLHF). Our method not only preserves the base models general capabilities but also significantly enhances its conversational abilities while notably reducing the generation of toxic outputs. Our approach holds significant implications for fields that demand a nuanced understanding and generation of responses such as customer service. We applied this methodology to Mistral the most popular base model thereby creating Mistral-Plus. Our validation across 11 general tasks demonstrates that Mistral-Plus outperforms similarly sized open-source base models and their corresponding instruct versions. Importantly the conversational abilities of Mistral-Plus were significantly improved indicating a substantial advancement over traditional SFT models in both safety and user preference alignment.
