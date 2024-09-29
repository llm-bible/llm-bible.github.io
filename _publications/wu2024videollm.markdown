---
layout: publication
title: Videollm45;mod Efficient Video45;language Streaming With Mixture45;of45;depths Vision Computation
authors: Wu Shiwei, Chen Joya, Lin Kevin Qinghong, Wang Qimeng, Gao Yan, Xu Qianli, Xu Tong, Hu Yao, Chen Enhong, Shou Mike Zheng
conference: "Arxiv"
year: 2024
bibkey: wu2024videollm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.16730"}
tags: ['Applications', 'Efficiency And Optimization', 'GPT', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
A well45;known dilemma in large vision45;language models (e.g. GPT45;4 LLaVA) is that while increasing the number of vision tokens generally enhances visual understanding it also significantly raises memory and computational costs especially in long45;term dense video frame streaming scenarios. Although learnable approaches like Q45;Former and Perceiver Resampler have been developed to reduce the vision token burden they overlook the context causally modeled by LLMs (i.e. key45;value cache) potentially leading to missed visual cues when addressing user queries. In this paper we introduce a novel approach to reduce vision compute by leveraging redundant vision tokens skipping layers rather than decreasing the number of vision tokens. Our method VideoLLM45;MoD is inspired by mixture45;of45;depths LLMs and addresses the challenge of numerous vision tokens in long45;term or streaming video. Specifically for each transformer layer we learn to skip the computation for a high proportion (e.g. 8037;) of vision tokens passing them directly to the next layer. This approach significantly enhances model efficiency achieving approximately textasciitilde4237; time and textasciitilde3037; memory savings for the entire training. Moreover our method reduces the computation in the context and avoid decreasing the vision tokens thus preserving or even improving performance compared to the vanilla model. We conduct extensive experiments to demonstrate the effectiveness of VideoLLM45;MoD showing its state45;of45;the45;art results on multiple benchmarks including narration forecasting and summarization tasks in COIN Ego4D and Ego45;Exo4D datasets.
