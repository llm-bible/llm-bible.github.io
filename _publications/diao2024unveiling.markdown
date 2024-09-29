---
layout: publication
title: Unveiling Encoder45;free Vision45;language Models
authors: Diao Haiwen, Cui Yufeng, Li Xiaotong, Wang Yueze, Lu Huchuan, Wang Xinlong
conference: "Arxiv"
year: 2024
bibkey: diao2024unveiling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.11832"}
  - {name: "Code", url: "https://github.com/baaivision/EVE"}
tags: ['Efficiency And Optimization', 'Ethics And Bias', 'Has Code', 'Model Architecture', 'Training Techniques']
---
Existing vision45;language models (VLMs) mostly rely on vision encoders to extract visual features followed by large language models (LLMs) for visual45;language tasks. However the vision encoders set a strong inductive bias in abstracting visual representation e.g. resolution aspect ratio and semantic priors which could impede the flexibility and efficiency of the VLMs. Training pure VLMs that accept the seamless vision and language inputs i.e. without vision encoders remains challenging and rarely explored. Empirical observations reveal that direct training without encoders results in slow convergence and large performance gaps. In this work we bridge the gap between encoder45;based and encoder45;free models and present a simple yet effective training recipe towards pure VLMs. Specifically we unveil the key aspects of training encoder45;free VLMs efficiently via thorough experiments (1) Bridging vision45;language representation inside one unified decoder; (2) Enhancing visual recognition capability via extra supervision. With these strategies we launch EVE an encoder45;free vision45;language model that can be trained and forwarded efficiently. Notably solely utilizing 35M publicly accessible data EVE can impressively rival the encoder45;based VLMs of similar capacities across multiple vision45;language benchmarks. It significantly outperforms the counterpart Fuyu45;8B with mysterious training procedures and undisclosed training data. We believe that EVE provides a transparent and efficient route for developing a pure decoder45;only architecture across modalities. Our code and models are publicly available at https://github.com/baaivision/EVE.
