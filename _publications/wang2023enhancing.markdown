---
layout: publication
title: Vaquita Enhancing Alignment In Llm45;assisted Video Understanding
authors: Wang Yizhou, Zhang Ruiyi, Wang Haoliang, Bhattacharya Uttaran, Fu Yun, Wu Gang
conference: "Arxiv"
year: 2023
bibkey: wang2023enhancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.02310"}
tags: ['Model Architecture', 'Pretraining Methods', 'Prompting', 'Tools', 'Transformer']
---
Recent advancements in language45;model45;based video understanding have been progressing at a remarkable pace spurred by the introduction of Large Language Models (LLMs). However the focus of prior research has been predominantly on devising a projection layer that maps video features to tokens an approach that is both rudimentary and inefficient. In our study we introduce a cutting45;edge framework VaQuitA designed to refine the synergy between video and textual information. At the data level instead of sampling frames uniformly we implement a sampling method guided by CLIP45;score rankings which enables a more aligned selection of frames with the given question. At the feature level we integrate a trainable Video Perceiver alongside a Visual45;Query Transformer (abbreviated as VQ45;Former) which bolsters the interplay between the input question and the video features. We also discover that incorporating a simple prompt Please be critical into the LLM input can substantially enhance its video comprehension capabilities. Our experimental results indicate that VaQuitA consistently sets a new benchmark for zero45;shot video question45;answering tasks and is adept at producing high45;quality multi45;turn video dialogues with users.
