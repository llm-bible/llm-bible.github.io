---
layout: publication
title: 'Lidar-llm: Exploring The Potential Of Large Language Models For 3D Lidar Understanding'
authors: Yang Senqiao, Liu Jiaming, Zhang Ray, Pan Mingjie, Guo Zoey, Li Xiaoqi, Chen Zehui, Gao Peng, Guo Yandong, Zhang Shanghang
conference: "Arxiv"
year: 2023
bibkey: yang2023lidar
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.14074"}
  - {name: "Code", url: "https://sites.google.com/view/lidar-llm"}
tags: ['Applications', 'Has Code', 'Language Modeling', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
'Recently, Large Language Models (LLMs) and Multimodal Large Language Models (MLLMs) have shown promise in instruction following and 2D image understanding. While these models are powerful, they have not yet been developed to comprehend the more challenging 3D physical scenes, especially when it comes to the sparse outdoor LiDAR data. In this paper, we introduce LiDAR-LLM, which takes raw LiDAR data as input and harnesses the remarkable reasoning capabilities of LLMs to gain a comprehensive understanding of outdoor 3D scenes. The central insight of our LiDAR-LLM is the reformulation of 3D outdoor scene cognition as a language modeling problem, encompassing tasks such as 3D captioning, 3D grounding, 3D question answering, etc. Specifically, due to the scarcity of 3D LiDAR-text pairing data, we introduce a three-stage training strategy and generate relevant datasets, progressively aligning the 3D modality with the language embedding space of LLM. Furthermore, we design a View-Aware Transformer (VAT) to connect the 3D encoder with the LLM, which effectively bridges the modality gap and enhances the LLM''s spatial orientation comprehension of visual features. Our experiments show that LiDAR-LLM possesses favorable capabilities to comprehend various instructions regarding 3D scenes and engage in complex spatial reasoning. LiDAR-LLM attains a 40.9 BLEU-1 on the 3D captioning task and achieves a 63.1\&#37; classification accuracy and a 14.3\&#37; BEV mIoU on the 3D grounding task. Web page: https://sites.google.com/view/lidar-llm'
