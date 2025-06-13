---
layout: publication
title: 'Balanced Token Pruning: Accelerating Vision Language Models Beyond Local Optimization'
authors: Kaiyuan Li, Xiaoyue Chen, Chen Gao, Yong Li, Xinlei Chen
conference: "Arxiv"
year: 2025
bibkey: li2025balanced
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.22038"}
tags: ['Multimodal Models', 'Model Architecture', 'Efficiency and Optimization', 'Reinforcement Learning', 'RAG', 'Pruning', 'Attention Mechanism']
---
Large Vision-Language Models (LVLMs) have shown impressive performance across multi-modal tasks by encoding images into thousands of tokens. However, the large number of image tokens results in significant computational overhead, and the use of dynamic high-resolution inputs further increases this burden. Previous approaches have attempted to reduce the number of image tokens through token pruning, typically by selecting tokens based on attention scores or image token diversity. Through empirical studies, we observe that existing methods often overlook the joint impact of pruning on both the current layer's output (local) and the outputs of subsequent layers (global), leading to suboptimal pruning decisions. To address this challenge, we propose Balanced Token Pruning (BTP), a plug-and-play method for pruning vision tokens. Specifically, our method utilizes a small calibration set to divide the pruning process into multiple stages. In the early stages, our method emphasizes the impact of pruning on subsequent layers, whereas in the deeper stages, the focus shifts toward preserving the consistency of local outputs. Extensive experiments across various LVLMs demonstrate the broad effectiveness of our approach on multiple benchmarks. Our method achieves a 78% compression rate while preserving 96.7% of the original models' performance on average.
