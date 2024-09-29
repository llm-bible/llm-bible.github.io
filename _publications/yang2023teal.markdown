---
layout: publication
title: TEAL Tokenize and Embed ALL for Multi-modal Large Language Models
authors: Yang Zhen, Zhang Yingxue, Meng Fandong, Zhou Jie
conference: "Arxiv"
year: 2023
bibkey: yang2023teal
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.04589"}
tags: ['GPT', 'Multimodal Models', 'Pretraining Methods']
---
Despite Multi-modal Large Language Models (MM-LLMs) have made exciting strides recently they are still struggling to efficiently model the interactions among multi-modal inputs and the generation in non-textual modalities. In this work we propose TEAL (Tokenize and Embed ALl) an approach to treat the input from any modality as a token sequence and learn a joint embedding space for all modalities. Specifically for the input from any modality TEAL first discretizes it into a token sequence with the off-the-shelf tokenizer and embeds the token sequence into a joint embedding space with a learnable embedding matrix. MM-LLMs just need to predict the multi-modal tokens autoregressively as the textual LLMs do. Finally the corresponding de-tokenizer is applied to generate the output in each modality based on the predicted token sequence. With the joint embedding space TEAL enables the frozen LLMs to perform both understanding and generation tasks involving non-textual modalities such as image and audio. Thus the textual LLM can just work as an interface and maintain its high performance in textual understanding and generation. Experiments show that TEAL achieves substantial improvements in multi-modal understanding and implements a simple scheme for multi-modal generations.
