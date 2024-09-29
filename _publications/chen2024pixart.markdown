---
layout: publication
title: "Pixart-\(\sigma\): Weak-to-strong Training Of Diffusion Transformer For 4K Text-to-image Generation"
authors: Chen Junsong, Ge Chongjian, Xie Enze, Wu Yue, Yao Lewei, Ren Xiaozhe, Wang Zhongdao, Luo Ping, Lu Huchuan, Li Zhenguo
conference: "Arxiv"
year: 2024
bibkey: chen2024pixart
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.04692"}
tags: ['Attention Mechanism', 'Efficiency And Optimization', 'Merging', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'RAG', 'Reinforcement Learning', 'Tools', 'Training Techniques', 'Transformer']
---
In this paper we introduce PixArt-(Sigma) a Diffusion Transformer model~(DiT) capable of directly generating images at 4K resolution. PixArt-(Sigma) represents a significant advancement over its predecessor PixArt-(alpha) offering images of markedly higher fidelity and improved alignment with text prompts. A key feature of PixArt-(Sigma) is its training efficiency. Leveraging the foundational pre-training of PixArt-(alpha) it evolves from the weaker baseline to a stronger model via incorporating higher quality data a process we term weak-to-strong training. The advancements in PixArt-(Sigma) are twofold (1) High-Quality Training Data PixArt-(Sigma) incorporates superior-quality image data paired with more precise and detailed image captions. (2) Efficient Token Compression we propose a novel attention module within the DiT framework that compresses both keys and values significantly improving efficiency and facilitating ultra-high-resolution image generation. Thanks to these improvements PixArt-(Sigma) achieves superior image quality and user prompt adherence capabilities with significantly smaller model size (0.6B parameters) than existing text-to-image diffusion models such as SDXL (2.6B parameters) and SD Cascade (5.1B parameters). Moreover PixArt-(Sigma)s capability to generate 4K images supports the creation of high-resolution posters and wallpapers efficiently bolstering the production of high-quality visual content in industries such as film and gaming.
