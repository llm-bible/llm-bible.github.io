---
layout: publication
title: Towards Unified Token Learning for Vision-Language Tracking
authors: Zheng Yaozong, Zhong Bineng, Liang Qihua, Li Guorong, Ji Rongrong, Li Xianxian
conference: "Arxiv"
year: 2023
bibkey: zheng2023towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.14103"}
tags: ['Efficiency And Optimization', 'Model Architecture', 'Multimodal Models', 'Tools']
---
In this paper we present a simple flexible and effective vision-language (VL) tracking pipeline termed which casts VL tracking as a token generation task. Traditional paradigms address VL tracking task indirectly with sophisticated prior designs making them over-specialize on the features of specific architectures or mechanisms. In contrast our proposed framework serializes language description and bounding box into a sequence of discrete tokens. In this new design paradigm all token queries are required to perceive the desired target and directly predict spatial coordinates of the target in an auto-regressive manner. The design without other prior modules avoids multiple sub-tasks learning and hand-designed loss functions significantly reducing the complexity of VL tracking modeling and allowing our tracker to use a simple cross-entropy loss as unified optimization objective for VL tracking task. Extensive experiments on TNL2K LaSOT LaSOT_ and OTB99-Lang benchmarks show that our approach achieves promising results compared to other state-of-the-arts.
