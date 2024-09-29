---
layout: publication
title: Long Context Alignment With Short Instructions And Synthesized Positions
authors: Wu Wenhao, Wang Yizhong, Fu Yao, Yue Xiang, Zhu Dawei, Li Sujian
conference: "Arxiv"
year: 2024
bibkey: wu2024long
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.03939"}
tags: ['GPT', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques']
---
Effectively handling instructions with extremely long context remains a challenge for Large Language Models (LLMs) typically necessitating high45;quality long data and substantial computational resources. This paper introduces Step45;Skipping Alignment (SkipAlign) a new technique designed to enhance the long45;context capabilities of LLMs in the phase of alignment without the need for additional efforts beyond training with original data length. SkipAlign is developed on the premise that long45;range dependencies are fundamental to enhancing an LLMs capacity of long context. Departing from merely expanding the length of input samples SkipAlign synthesizes long45;range dependencies from the aspect of positions indices. This is achieved by the strategic insertion of skipped positions within instruction45;following samples which utilizes the semantic structure of the data to effectively expand the context. Through extensive experiments on base models with a variety of context window sizes SkipAlign demonstrates its effectiveness across a spectrum of long45;context tasks. Particularly noteworthy is that with a careful selection of the base model and alignment datasets SkipAlign with only 6B parameters achieves its best performance and comparable with strong baselines like GPT45;3.545;Turbo45;16K on LongBench.
