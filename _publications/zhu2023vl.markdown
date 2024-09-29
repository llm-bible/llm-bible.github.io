---
layout: publication
title: VL45;GPT A Generative Pre45;trained Transformer For Vision And Language Understanding And Generation
authors: Zhu Jinguo, Ding Xiaohan, Ge Yixiao, Ge Yuying, Zhao Sijie, Zhao Hengshuang, Wang Xiaohua, Shan Ying
conference: "Arxiv"
year: 2023
bibkey: zhu2023vl
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.09251"}
tags: ['Applications', 'GPT', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning', 'Tools', 'Training Techniques', 'Transformer']
---
In this work we introduce Vision45;Language Generative Pre45;trained Transformer (VL45;GPT) a transformer model proficient at concurrently perceiving and generating visual and linguistic data. VL45;GPT achieves a unified pre45;training approach for both image and text modalities by employing a straightforward auto45;regressive objective thereby enabling the model to process image and text as seamlessly as a language model processes text. To accomplish this we initially propose a novel image tokenizer45;detokenizer framework for visual data specifically designed to transform raw images into a sequence of continuous embeddings and reconstruct them accordingly. In combination with the existing text tokenizer and detokenizer this framework allows for the encoding of interleaved image45;text data into a multimodal sequence which can subsequently be fed into the transformer model. Consequently VL45;GPT can perform large45;scale pre45;training on multimodal corpora utilizing a unified auto45;regressive objective (i.e. next45;token prediction). Upon completion of pre45;training VL45;GPT exhibits remarkable zero45;shot and few45;shot performance across a diverse range of vision and language understanding and generation tasks including image captioning visual question answering text45;to45;image generation and more. Additionally the pre45;trained model retrains in45;context learning capabilities when provided with multimodal prompts. We further conduct instruction tuning on our VL45;GPT highlighting its exceptional potential for multimodal assistance. The source code and model weights shall be released.
