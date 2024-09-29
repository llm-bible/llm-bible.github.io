---
layout: publication
title: DEEM Diffusion Models Serve As The Eyes Of Large Language Models For Image Perception
authors: Luo Run, Li Yunshui, Chen Longze, He Wanwei, Lin Ting-en, Liu Ziqiang, Zhang Lei, Song Zikai, Xia Xiaobo, Liu Tongliang, Yang Min, Hui Binyuan
conference: "Arxiv"
year: 2024
bibkey: luo2024deem
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.15232"}
tags: ['Merging', 'Multimodal Models', 'Prompting', 'Reinforcement Learning', 'Security', 'Training Techniques']
---
The development of large language models (LLMs) has significantly advanced the emergence of large multimodal models (LMMs). While LMMs have achieved tremendous success by promoting the synergy between multimodal comprehension and creation they often face challenges when confronted with out-of-distribution data. This is primarily due to their reliance on image encoders trained to encode images into task-relevant features which may lead them to disregard irrelevant details. Delving into the modeling capabilities of diffusion models for images naturally prompts the question Can diffusion models serve as the eyes of large language models for image perception In this paper we propose DEEM a simple and effective approach that utilizes the generative feedback of diffusion models to align the semantic distributions of the image encoder. This addresses the drawbacks of previous methods that solely relied on image encoders like ViT thereby enhancing the models resilience against out-of-distribution samples and reducing visual hallucinations. Importantly this is achieved without requiring additional training modules and with fewer training parameters. We extensively evaluated DEEM on both our newly constructed RobustVQA benchmark and another well-known benchmark POPE for object hallucination. Compared to the state-of-the-art interleaved content generation models DEEM exhibits enhanced robustness and a superior capacity to alleviate model hallucinations while utilizing fewer trainable parameters less pre-training data (1037;) and a smaller base model size.
