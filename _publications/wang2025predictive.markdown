---
layout: publication
title: 'Plan2align: Predictive Planning Based Test-time Preference Alignment For Large Language Models'
authors: Kuang-da Wang, Teng-ruei Chen, Yu Heng Hung, Guo-xun Ko, Shuoyang Ding, Yueh-hua Wu, Yu-chiang Frank Wang, Chao-han Huck Yang, Wen-chih Peng, Ping-chun Hsieh
conference: "Arxiv"
year: 2025
bibkey: wang2025predictive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.20795"}
tags: ['Fine-Tuning', 'Tools', 'Efficiency and Optimization', 'Applications', 'Language Modeling', 'WMT', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods', 'Prompting']
---
Aligning Large Language Models with Preference Fine-Tuning is often resource-intensive. Test-time alignment techniques that do not modify the underlying models, such as prompting and guided decodings, offer a lightweight alternative. However, existing test-time alignment methods primarily improve short responses and fail to ensure coherence over extended contexts due to the myopic nature of token-level alignment. Moreover, these methods often incur a slowdown during inference. To address these challenges, we propose Plan2Align, a test-time alignment framework that formulates text generation as a predictive planning problem. Plan2Align adapts Model Predictive Control (MPC) to iteratively refine output by rolling out multiple complete responses and optimizing each segment. To more rigorously evaluate the effectiveness and efficiency, we focus on the more challenging task of long-text generation. Experiments on the long-form response subset of the HH-RLHF dataset and the WMT'24 Discourse-Level Literary Translation demonstrate that Plan2Align significantly enhances the performance of base LLMs. Compared to existing training-time and test-time alignment methods on LLaMA-3.1 8B, Plan2Align achieves comparable or superior results, while also delivering improved inference efficiency relative to prior test-time alignment approaches.
