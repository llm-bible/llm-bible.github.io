---
layout: publication
title: 'Adaptvision: Dynamic Input Scaling In Mllms For Versatile Scene Understanding'
authors: Wang Yonghui, Zhou Wengang, Feng Hao, Li Houqiang
conference: "Arxiv"
year: 2024
bibkey: wang2024dynamic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.16986"}
  - {name: "Code", url: "https://github.com/harrytea/AdaptVision"}
tags: ['Has Code', 'Multimodal Models', 'Reinforcement Learning']
---
'Over the past few years, the advancement of Multimodal Large Language Models (MLLMs) has captured the wide interest of researchers, leading to numerous innovations to enhance MLLMs'' comprehension. In this paper, we present AdaptVision, a multimodal large language model specifically designed to dynamically process input images at varying resolutions. We hypothesize that the requisite number of visual tokens for the model is contingent upon both the resolution and content of the input image. Generally, natural images with a lower information density can be effectively interpreted by the model using fewer visual tokens at reduced resolutions. In contrast, images containing textual content, such as documents with rich text, necessitate a higher number of visual tokens for accurate text interpretation due to their higher information density. Building on this insight, we devise a dynamic image partitioning module that adjusts the number of visual tokens according to the size and aspect ratio of images. This method mitigates distortion effects that arise from resizing images to a uniform resolution and dynamically optimizing the visual tokens input to the LLMs. Our model is capable of processing images with resolutions up to \(1008\times 1008\). Extensive experiments across various datasets demonstrate that our method achieves impressive performance in handling vision-language tasks in both natural and text-related scenes. The source code and dataset are now publicly available at \url\{https://github.com/harrytea/AdaptVision\}.'
