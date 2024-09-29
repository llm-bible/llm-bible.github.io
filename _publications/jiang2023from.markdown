---
layout: publication
title: From CLIP To DINO: Visual Encoders Shout In Multi-modal Large Language Models
authors: Jiang Dongsheng, Liu Yuchen, Liu Songlin, Zhao Jin'e, Zhang Hao, Gao Zhen, Zhang Xiaopeng, Li Jin, Xiong Hongkai
conference: "Arxiv"
year: 2023
bibkey: jiang2023from
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.08825"}
tags: ['Applications', 'Merging']
---
Multi-modal Large Language Models (MLLMs) have made significant strides in expanding the capabilities of Large Language Models (LLMs) through the incorporation of visual perception interfaces. Despite the emergence of exciting applications and the availability of diverse instruction tuning data existing approaches often rely on CLIP or its variants as the visual branch and merely extract features from the deep layers. However these methods lack a comprehensive analysis of the visual encoders in MLLMs. In this paper we conduct an extensive investigation into the effectiveness of different vision encoders within MLLMs. Our findings reveal that the shallow layer features of CLIP offer particular advantages for fine-grained tasks such as grounding and region understanding. Surprisingly the vision-only model DINO which is not pretrained with text-image alignment demonstrates promising performance as a visual branch within MLLMs. By simply equipping it with an MLP layer for alignment DINO surpasses CLIP in fine-grained related perception tasks. Building upon these observations we propose a simple yet effective feature merging strategy named COMM that integrates CLIP and DINO with Multi-level features Merging to enhance the visual capabilities of MLLMs. We evaluate COMM through comprehensive experiments on a wide range of benchmarks including image captioning visual question answering visual grounding and object hallucination. Experimental results demonstrate the superior performance of COMM compared to existing methods showcasing its enhanced visual capabilities within MLLMs.
