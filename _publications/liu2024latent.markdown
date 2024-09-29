---
layout: publication
title: Latent Guard A Safety Framework For Text-to-image Generation
authors: Liu Runtao, Khakzar Ashkan, Gu Jindong, Chen Qifeng, Torr Philip, Pizzati Fabio
conference: "Arxiv"
year: 2024
bibkey: liu2024latent
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.08031"}
  - {name: "Code", url: "https://latentguard.github.io/"}
tags: ['Has Code', 'Pretraining Methods', 'Responsible AI', 'Tools', 'Training Techniques']
---
With the ability to generate high-quality images text-to-image (T2I) models can be exploited for creating inappropriate content. To prevent misuse existing safety measures are either based on text blacklists which can be easily circumvented or harmful content classification requiring large datasets for training and offering low flexibility. Hence we propose Latent Guard a framework designed to improve safety measures in text-to-image generation. Inspired by blacklist-based approaches Latent Guard learns a latent space on top of the T2I models text encoder where it is possible to check the presence of harmful concepts in the input text embeddings. Our proposed framework is composed of a data generation pipeline specific to the task using large language models ad-hoc architectural components and a contrastive learning strategy to benefit from the generated data. The effectiveness of our method is verified on three datasets and against four baselines. Code and data will be shared at https://latentguard.github.io/."
