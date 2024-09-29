---
layout: publication
title: Chain45;of45;spot Interactive Reasoning Improves Large Vision45;language Models
authors: Liu Zuyan, Dong Yuhao, Rao Yongming, Zhou Jie, Lu Jiwen
conference: "Arxiv"
year: 2024
bibkey: liu2024chain
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.12966"}
  - {name: "Code", url: "https://github.com/dongyh20/Chain&#45;of&#45;Spot"}
tags: ['Applications', 'Has Code', 'Multimodal Models']
---
In the realm of vision45;language understanding the proficiency of models in interpreting and reasoning over visual content has become a cornerstone for numerous applications. However it is challenging for the visual encoder in Large Vision45;Language Models (LVLMs) to extract useful features tailored to questions that aid the language models response. Furthermore a common practice among existing LVLMs is to utilize lower45;resolution images which restricts the ability for visual recognition. Our work introduces the Chain45;of45;Spot (CoS) method which we describe as Interactive Reasoning a novel approach that enhances feature extraction by focusing on key regions of interest (ROI) within the image corresponding to the posed questions or instructions. This technique allows LVLMs to access more detailed visual information without altering the original image resolution thereby offering multi45;granularity image features. By integrating Chain45;of45;Spot with instruct45;following LLaVA45;1.5 models the process of image reasoning consistently improves performance across a wide range of multimodal datasets and benchmarks without bells and whistles and achieves new state45;of45;the45;art results. Our empirical findings demonstrate a significant improvement in LVLMs ability to understand and reason about visual content paving the way for more sophisticated visual instruction45;following applications. Code and models are available at https://github.com/dongyh20/Chain&#45;of&#45;Spot
