---
layout: publication
title: 'VL-GPT: A Generative Pre-trained Transformer For Vision And Language Understanding And Generation'
authors: Zhu Jinguo, Ding Xiaohan, Ge Yixiao, Ge Yuying, Zhao Sijie, Zhao Hengshuang, Wang Xiaohua, Shan Ying
conference: "Arxiv"
year: 2023
bibkey: zhu2023vl
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.09251"}
tags: ['Applications', 'Few Shot', 'GPT', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning', 'Tools', 'Training Techniques', 'Transformer']
---
In this work, we introduce Vision-Language Generative Pre-trained Transformer
(VL-GPT), a transformer model proficient at concurrently perceiving and
generating visual and linguistic data. VL-GPT achieves a unified pre-training
approach for both image and text modalities by employing a straightforward
auto-regressive objective, thereby enabling the model to process image and text
as seamlessly as a language model processes text. To accomplish this, we
initially propose a novel image tokenizer-detokenizer framework for visual
data, specifically designed to transform raw images into a sequence of
continuous embeddings and reconstruct them accordingly. In combination with the
existing text tokenizer and detokenizer, this framework allows for the encoding
of interleaved image-text data into a multimodal sequence, which can
subsequently be fed into the transformer model. Consequently, VL-GPT can
perform large-scale pre-training on multimodal corpora utilizing a unified
auto-regressive objective (i.e., next-token prediction). Upon completion of
pre-training, VL-GPT exhibits remarkable zero-shot and few-shot performance
across a diverse range of vision and language understanding and generation
tasks, including image captioning, visual question answering, text-to-image
generation, and more. Additionally, the pre-trained model retrains in-context
learning capabilities when provided with multimodal prompts. We further conduct
instruction tuning on our VL-GPT, highlighting its exceptional potential for
multimodal assistance. The source code and model weights shall be released.
