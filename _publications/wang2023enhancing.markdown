---
layout: publication
title: "Vaquita: Enhancing Alignment In Llm-assisted Video Understanding"
authors: Wang Yizhou, Zhang Ruiyi, Wang Haoliang, Bhattacharya Uttaran, Fu Yun, Wu Gang
conference: "Arxiv"
year: 2023
bibkey: wang2023enhancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.02310"}
tags: ['Model Architecture', 'Pretraining Methods', 'Prompting', 'Tools', 'Transformer']
---
Recent advancements in language-model-based video understanding have been progressing at a remarkable pace spurred by the introduction of Large Language Models (LLMs). However the focus of prior research has been predominantly on devising a projection layer that maps video features to tokens an approach that is both rudimentary and inefficient. In our study we introduce a cutting-edge framework VaQuitA designed to refine the synergy between video and textual information. At the data level instead of sampling frames uniformly we implement a sampling method guided by CLIP-score rankings which enables a more aligned selection of frames with the given question. At the feature level we integrate a trainable Video Perceiver alongside a Visual-Query Transformer (abbreviated as VQ-Former) which bolsters the interplay between the input question and the video features. We also discover that incorporating a simple prompt Please be critical into the LLM input can substantially enhance its video comprehension capabilities. Our experimental results indicate that VaQuitA consistently sets a new benchmark for zero-shot video question-answering tasks and is adept at producing high-quality multi-turn video dialogues with users.
