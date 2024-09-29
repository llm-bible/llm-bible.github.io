---
layout: publication
title: Emu Generative Pretraining In Multimodality
authors: Sun Quan, Yu Qiying, Cui Yufeng, Zhang Fan, Zhang Xiaosong, Wang Yueze, Gao Hongcheng, Liu Jingjing, Huang Tiejun, Wang Xinlong
conference: "Arxiv"
year: 2023
bibkey: sun2023emu
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2307.05222"}
tags: ['Applications', 'Few Shot', 'Fine Tuning', 'GPT', 'Language Modeling', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
We present Emu a Transformer-based multimodal foundation model which can seamlessly generate images and texts in multimodal context. This omnivore model can take in any single-modality or multimodal data input indiscriminately (e.g. interleaved image text and video) through a one-model-for-all autoregressive training process. First visual signals are encoded into embeddings and together with text tokens form an interleaved input sequence. Emu is then end-to-end trained with a unified objective of classifying the next text token or regressing the next visual embedding in the multimodal sequence. This versatile multimodality empowers the exploration of diverse pretraining data sources at scale such as videos with interleaved frames and text webpages with interleaved images and text as well as web-scale image-text pairs and video-text pairs. Emu can serve as a generalist multimodal interface for both image-to-text and text-to-image tasks and supports in-context image and text generation. Across a broad range of zero-shot/few-shot tasks including image captioning visual question answering video question answering and text-to-image generation Emu demonstrates superb performance compared to state-of-the-art large multimodal models. Extended capabilities such as multimodal assistants via instruction tuning are also demonstrated with impressive performance.
