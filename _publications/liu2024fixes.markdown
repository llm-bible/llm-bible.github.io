---
layout: publication
title: 'Proofread: Fixes All Errors With One Tap'
authors: Liu Renjie, Zhang Yanxiang, Zhu Yun, Sun Haicheng, Zhang Yuanbo, Huang Michael Xuelin, Cai Shanqing, Meng Lei, Zhai Shumin
conference: "Arxiv"
year: 2024
bibkey: liu2024fixes
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.04523"}
tags: ['Agentic', 'Applications', 'Efficiency And Optimization', 'Fine Tuning', 'Quantization', 'RAG', 'Reinforcement Learning']
---
"The impressive capabilities in Large Language Models (LLMs) provide a powerful approach to reimagine users' typing experience. This paper demonstrates Proofread, a novel Gboard feature powered by a server-side LLM in Gboard, enabling seamless sentence-level and paragraph-level corrections with a single tap. We describe the complete system in this paper, from data generation, metrics design to model tuning and deployment. To obtain models with sufficient quality, we implement a careful data synthetic pipeline tailored to online use cases, design multifaceted metrics, employ a two-stage tuning approach to acquire the dedicated LLM for the feature: the Supervised Fine Tuning (SFT) for foundational quality, followed by the Reinforcement Learning (RL) tuning approach for targeted refinement. Specifically, we find sequential tuning on Rewrite and proofread tasks yields the best quality in SFT stage, and propose global and direct rewards in the RL tuning stage to seek further improvement. Extensive experiments on a human-labeled golden set showed our tuned PaLM2-XS model achieved 85.56\&#37; good ratio. We launched the feature to Pixel 8 devices by serving the model on TPU v5 in Google Cloud, with thousands of daily active users. Serving latency was significantly reduced by quantization, bucket inference, text segmentation, and speculative decoding. Our demo could be seen in \href\{https://youtu.be/4ZdcuiwFU7I\}\{Youtube\}."
