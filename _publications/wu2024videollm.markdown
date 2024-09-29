---
layout: publication
title: 'Videollm-mod: Efficient Video-language Streaming With Mixture-of-depths Vision Computation'
authors: Wu Shiwei, Chen Joya, Lin Kevin Qinghong, Wang Qimeng, Gao Yan, Xu Qianli, Xu Tong, Hu Yao, Chen Enhong, Shou Mike Zheng
conference: "Arxiv"
year: 2024
bibkey: wu2024videollm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.16730"}
tags: ['Applications', 'Efficiency And Optimization', 'GPT', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
A well-known dilemma in large vision-language models (e.g. GPT-4 LLaVA) is that while increasing the number of vision tokens generally enhances visual understanding it also significantly raises memory and computational costs especially in long-term dense video frame streaming scenarios. Although learnable approaches like Q-Former and Perceiver Resampler have been developed to reduce the vision token burden they overlook the context causally modeled by LLMs (i.e. key-value cache) potentially leading to missed visual cues when addressing user queries. In this paper we introduce a novel approach to reduce vision compute by leveraging redundant vision tokens skipping layers rather than decreasing the number of vision tokens. Our method VideoLLM-MoD is inspired by mixture-of-depths LLMs and addresses the challenge of numerous vision tokens in long-term or streaming video. Specifically for each transformer layer we learn to skip the computation for a high proportion (e.g. 8037;) of vision tokens passing them directly to the next layer. This approach significantly enhances model efficiency achieving approximately (textasciitilde)4237; time and (textasciitilde)3037; memory savings for the entire training. Moreover our method reduces the computation in the context and avoid decreasing the vision tokens thus preserving or even improving performance compared to the vanilla model. We conduct extensive experiments to demonstrate the effectiveness of VideoLLM-MoD showing its state-of-the-art results on multiple benchmarks including narration forecasting and summarization tasks in COIN Ego4D and Ego-Exo4D datasets.
