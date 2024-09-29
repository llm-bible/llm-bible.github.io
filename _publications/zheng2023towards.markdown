---
layout: publication
title: Towards Unified Token Learning For Vision45;language Tracking
authors: Zheng Yaozong, Zhong Bineng, Liang Qihua, Li Guorong, Ji Rongrong, Li Xianxian
conference: "Arxiv"
year: 2023
bibkey: zheng2023towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.14103"}
tags: ['Applications', 'Efficiency And Optimization', 'Model Architecture', 'Tools']
---
In this paper we present a simple flexible and effective vision45;language (VL) tracking pipeline termed textbf123;MMTrack125; which casts VL tracking as a token generation task. Traditional paradigms address VL tracking task indirectly with sophisticated prior designs making them over45;specialize on the features of specific architectures or mechanisms. In contrast our proposed framework serializes language description and bounding box into a sequence of discrete tokens. In this new design paradigm all token queries are required to perceive the desired target and directly predict spatial coordinates of the target in an auto45;regressive manner. The design without other prior modules avoids multiple sub45;tasks learning and hand45;designed loss functions significantly reducing the complexity of VL tracking modeling and allowing our tracker to use a simple cross45;entropy loss as unified optimization objective for VL tracking task. Extensive experiments on TNL2K LaSOT LaSOT95;123;rm123;ext125;125; and OTB9945;Lang benchmarks show that our approach achieves promising results compared to other state45;of45;the45;arts.
