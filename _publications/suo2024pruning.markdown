---
layout: publication
title: 'Pruning All-rounder: Rethinking And Improving Inference Efficiency For Large Vision Language Models'
authors: Wei Suo, Ji Ma, Mengyang Sun, Lin Yuanbo Wu, Peng Wang, Yanning Zhang
conference: "Arxiv"
year: 2024
bibkey: suo2024pruning
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.06458'}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Tools', 'Pruning', 'Multimodal Models', 'Pretraining Methods']
---
Although Large Vision-Language Models (LVLMs) have achieved impressive
results, their high computational cost poses a significant barrier to wider
application. To enhance inference efficiency, most existing approaches depend
on parameter-dependent or token-dependent strategies to reduce computational
demands. However, these methods typically require complex training processes
and struggle to consistently select the most relevant tokens. In this paper, we
systematically analyze the above challenges and provide a series of valuable
insights for inference acceleration. Based on these findings, we propose a
novel framework, the Pruning All-Rounder (PAR). Different from previous works,
PAR develops a meta-router to adaptively organize pruning flows across both
tokens and layers. With a self-supervised learning manner, our method achieves
a superior balance between performance and efficiency. Notably, PAR is highly
flexible, offering multiple pruning versions to address a range of pruning
scenarios. The code for this work will be made publicly available.
