---
layout: publication
title: 'Chain-of-spot: Interactive Reasoning Improves Large Vision-language Models'
authors: Liu Zuyan, Dong Yuhao, Rao Yongming, Zhou Jie, Lu Jiwen
conference: "Arxiv"
year: 2024
bibkey: liu2024chain
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.12966"}
  - {name: "Code", url: "https://github.com/dongyh20/Chain-of-Spot"}
tags: ['Applications', 'Has Code', 'Multimodal Models']
---
In the realm of vision-language understanding the proficiency of models in interpreting and reasoning over visual content has become a cornerstone for numerous applications. However it is challenging for the visual encoder in Large Vision-Language Models (LVLMs) to extract useful features tailored to questions that aid the language models response. Furthermore a common practice among existing LVLMs is to utilize lower-resolution images which restricts the ability for visual recognition. Our work introduces the Chain-of-Spot (CoS) method which we describe as Interactive Reasoning a novel approach that enhances feature extraction by focusing on key regions of interest (ROI) within the image corresponding to the posed questions or instructions. This technique allows LVLMs to access more detailed visual information without altering the original image resolution thereby offering multi-granularity image features. By integrating Chain-of-Spot with instruct-following LLaVA-1.5 models the process of image reasoning consistently improves performance across a wide range of multimodal datasets and benchmarks without bells and whistles and achieves new state-of-the-art results. Our empirical findings demonstrate a significant improvement in LVLMs ability to understand and reason about visual content paving the way for more sophisticated visual instruction-following applications. Code and models are available at https://github.com/dongyh20/Chain-of-Spot"
