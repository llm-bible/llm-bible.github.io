---
layout: publication
title: Visually Guided Generative Text-Layout Pre-training for Document Intelligence
authors: Mao Zhiming, Bai Haoli, Hou Lu, Wei Jiansheng, Jiang Xin, Liu Qun, Wong Kam-fai
conference: "Arxiv"
year: 2024
bibkey: mao2024visually
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.16516"}
tags: ['Applications', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
Prior study shows that pre-training techniques can boost the performance of visual document understanding (VDU) which typically requires models to gain abilities to perceive and reason both document texts and layouts (e.g. locations of texts and table-cells). To this end we propose visually guided generative text-layout pre-training named ViTLP. Given a document image the model optimizes hierarchical language and layout modeling objectives to generate the interleaved text and layout sequence. In addition to address the limitation of processing long documents by Transformers we introduce a straightforward yet effective multi-segment generative pre-training scheme facilitating ViTLP to process word-intensive documents of any length. ViTLP can function as a native OCR model to localize and recognize texts of document images. Besides ViTLP can be effectively applied to various downstream VDU tasks. Extensive experiments show that ViTLP achieves competitive performance over existing baselines on benchmark VDU tasks including information extraction document classification and document question answering.
