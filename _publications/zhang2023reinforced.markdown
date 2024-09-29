---
layout: publication
title: 'Reinforced UI Instruction Grounding: Towards A Generic UI Task Automation API'
authors: Zhang Zhizheng, Xie Wenxuan, Zhang Xiaoyi, Lu Yan
conference: "Arxiv"
year: 2023
bibkey: zhang2023reinforced
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.04716"}
tags: ['Agentic', 'Multimodal Models', 'Prompting', 'Reinforcement Learning', 'Tools']
---
Recent popularity of Large Language Models (LLMs) has opened countless possibilities in automating numerous AI tasks by connecting LLMs to various domain-specific models or APIs where LLMs serve as dispatchers while domain-specific models or APIs are action executors. Despite the vast numbers of domain-specific models/APIs they still struggle to comprehensively cover super diverse automation demands in the interaction between human and User Interfaces (UIs). In this work we build a multimodal model to ground natural language instructions in given UI screenshots as a generic UI task automation executor. This metadata-free grounding model consisting of a visual encoder and a language decoder is first pretrained on well studied document understanding tasks and then learns to decode spatial information from UI screenshots in a promptable way. To facilitate the exploitation of image-to-text pretrained knowledge we follow the pixel-to-sequence paradigm to predict geometric coordinates in a sequence of tokens using a language decoder. We further propose an innovative Reinforcement Learning (RL) based algorithm to supervise the tokens in such sequence jointly with visually semantic metrics which effectively strengthens the spatial decoding capability of the pixel-to-sequence paradigm. Extensive experiments demonstrate our proposed reinforced UI instruction grounding model outperforms the state-of-the-art methods by a clear margin and shows the potential as a generic UI task automation API.
