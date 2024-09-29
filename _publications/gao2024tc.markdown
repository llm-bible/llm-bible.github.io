---
layout: publication
title: Tc45;llava Rethinking The Transfer From Image To Video Understanding With Temporal Considerations
authors: Gao Mingze, Liu Jingyu, Li Mingda, Xie Jiangtao, Liu Qingbin, Zhao Bo, Chen Xi, Xiong Hui
conference: "Arxiv"
year: 2024
bibkey: gao2024tc
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.03206"}
tags: ['Applications', 'Attention Mechanism', 'Fine Tuning', 'Model Architecture', 'Multimodal Models']
---
Multimodal Large Language Models (MLLMs) have significantly improved performance across various image45;language applications. Recently there has been a growing interest in adapting image pre45;trained MLLMs for video45;related tasks. However most efforts concentrate on enhancing the vision encoder and projector components while the core part Large Language Models (LLMs) remains comparatively under45;explored. In this paper we propose two strategies to enhance the models capability in video understanding tasks by improving inter45;layer attention computation in LLMs. Specifically the first approach focuses on the enhancement of Rotary Position Embedding (RoPE) with Temporal45;Aware Dual RoPE which introduces temporal position information to strengthen the MLLMs temporal modeling capabilities while preserving the relative position relationships of both visual and text tokens. The second approach involves enhancing the Attention Mask with the Frame45;wise Block Causal Attention Mask a simple yet effective method that broadens visual token interactions within and across video frames while maintaining the causal inference mechanism. Based on these proposed methods we adapt LLaVA for video understanding tasks naming it Temporal45;Considered LLaVA (TC45;LLaVA). Our TC45;LLaVA achieves new state45;of45;the45;art performance across various video understanding benchmarks with only supervised fine45;tuning (SFT) on video45;related datasets.
