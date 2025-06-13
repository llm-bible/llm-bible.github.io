---
layout: publication
title: 'DAMA: Data- And Model-aware Alignment Of Multi-modal Llms'
authors: Jinda Lu, Junkang Wu, Jinghan Li, Xiaojun Jia, Shuo Wang, Yifan Zhang, Junfeng Fang, Xiang Wang, Xiangnan He
conference: "Arxiv"
year: 2025
bibkey: lu2025data
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.01943"}
tags: ['Efficiency and Optimization', 'GPT', 'Model Architecture', 'Reinforcement Learning']
---
Direct Preference Optimization (DPO) has shown effectiveness in aligning
multi-modal large language models (MLLM) with human preferences. However,
existing methods exhibit an imbalanced responsiveness to the data of varying
hardness, tending to overfit on the easy-to-distinguish data while underfitting
on the hard-to-distinguish data. In this paper, we propose Data- and
Model-aware DPO (DAMA) to dynamically adjust the optimization process from two
key aspects: (1) a data-aware strategy that incorporates data hardness, and (2)
a model-aware strategy that integrates real-time model responses. By combining
the two strategies, DAMA enables the model to effectively adapt to data with
varying levels of hardness. Extensive experiments on five benchmarks
demonstrate that DAMA not only significantly enhances the trustworthiness, but
also improves the effectiveness over general tasks. For instance, on the
Object-HalBench, our DAMA-7B reduces response-level and mentioned-level
hallucination by 90.0% and 95.3%, respectively, surpassing the performance of
GPT-4V.
