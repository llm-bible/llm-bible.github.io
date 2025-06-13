---
layout: publication
title: 'Openomni: Advancing Open-source Omnimodal Large Language Models With Progressive Multimodal Alignment And Real-time Self-aware Emotional Speech Synthesis'
authors: Run Luo, Ting-en Lin, Haonan Zhang, Yuchuan Wu, Xiong Liu, Min Yang, Yongbin Li, Longze Chen, Jiaming Li, Lei Zhang, Yangyi Chen, Xiaobo Xia, Hamid Alinejad-rokny, Fei Huang
conference: "Arxiv"
year: 2025
bibkey: luo2025advancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.04561"}
tags: ['Tools', 'GPT', 'Efficiency and Optimization', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods', 'Multimodal Models']
---
Recent advancements in omnimodal learning have significantly improved understanding and generation across images, text, and speech, yet these developments remain predominantly confined to proprietary models. The lack of high-quality omnimodal datasets and the challenges of real-time emotional speech synthesis have notably hindered progress in open-source research. To address these limitations, we introduce \name, a two-stage training framework that integrates omnimodal alignment and speech generation to develop a state-of-the-art omnimodal large language model. In the alignment phase, a pre-trained speech model undergoes further training on text-image tasks, enabling (near) zero-shot generalization from vision to speech, outperforming models trained on tri-modal datasets. In the speech generation phase, a lightweight decoder is trained on speech tasks with direct preference optimization, enabling real-time emotional speech synthesis with high fidelity. Experiments show that \name surpasses state-of-the-art models across omnimodal, vision-language, and speech-language benchmarks. It achieves a 4-point absolute improvement on OmniBench over the leading open-source model VITA, despite using 5x fewer training samples and a smaller model size (7B vs. 7x8B). Additionally, \name achieves real-time speech generation with <1s latency at non-autoregressive mode, reducing inference time by 5x compared to autoregressive methods, and improves emotion classification accuracy by 7.7%
