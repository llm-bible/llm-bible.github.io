---
layout: publication
title: Ferret Refer And Ground Anything Anywhere At Any Granularity
authors: You Haoxuan, Zhang Haotian, Gan Zhe, Du Xianzhi, Zhang Bowen, Wang Zirui, Cao Liangliang, Chang Shih-fu, Yang Yinfei
conference: "Arxiv"
year: 2023
bibkey: you2023refer
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.07704"}
  - {name: "Code", url: "https://github.com/apple/ml&#45;ferret"}
tags: ['Has Code', 'Multimodal Models', 'Security']
---
We introduce Ferret a new Multimodal Large Language Model (MLLM) capable of understanding spatial referring of any shape or granularity within an image and accurately grounding open45;vocabulary descriptions. To unify referring and grounding in the LLM paradigm Ferret employs a novel and powerful hybrid region representation that integrates discrete coordinates and continuous features jointly to represent a region in the image. To extract the continuous features of versatile regions we propose a spatial45;aware visual sampler adept at handling varying sparsity across different shapes. Consequently Ferret can accept diverse region inputs such as points bounding boxes and free45;form shapes. To bolster the desired capability of Ferret we curate GRIT a comprehensive refer45;and45;ground instruction tuning dataset including 1.1M samples that contain rich hierarchical spatial knowledge with 95K hard negative data to promote model robustness. The resulting model not only achieves superior performance in classical referring and grounding tasks but also greatly outperforms existing MLLMs in region45;based and localization45;demanded multimodal chatting. Our evaluations also reveal a significantly improved capability of describing image details and a remarkable alleviation in object hallucination. Code and data will be available at https://github.com/apple/ml&#45;ferret
