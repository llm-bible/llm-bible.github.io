---
layout: publication
title: "Understanding And Patching Compositional Reasoning In Llms"
authors: Li Zhaoyi, Jiang Gangwei, Xie Hong, Song Linqi, Lian Defu, Wei Ying
conference: "Arxiv"
year: 2024
bibkey: li2024understanding
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.14328"}
tags: ['Attention Mechanism', 'Fine Tuning', 'Model Architecture', 'RAG', 'Reinforcement Learning', 'Tools', 'Transformer']
---
LLMs have marked a revolutonary shift yet they falter when faced with compositional reasoning tasks. Our research embarks on a quest to uncover the root causes of compositional reasoning failures of LLMs uncovering that most of them stem from the improperly generated or leveraged implicit reasoning results. Inspired by our empirical findings we resort to Logit Lens and an intervention experiment to dissect the inner hidden states of LLMs. This deep dive reveals that implicit reasoning results indeed surface within middle layers and play a causative role in shaping the final explicit reasoning results. Our exploration further locates multi-head self-attention (MHSA) modules within these layers which emerge as the linchpins in accurate generation and leveraing of implicit reasoning results. Grounded on the above findings we develop CREME a lightweight method to patch errors in compositional reasoning via editing the located MHSA modules. Our empirical evidence stands testament to CREMEs effectiveness paving the way for autonomously and continuously enhancing compositional reasoning capabilities in language models.
