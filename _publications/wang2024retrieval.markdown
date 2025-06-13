---
layout: publication
title: 'RAC3: Retrieval-augmented Corner Case Comprehension For Autonomous Driving With Vision-language Models'
authors: Yujin Wang, Quanfeng Liu, Jiaqi Fan, Jinlong Hong, Hongqing Chu, Mengjian Tian, Bingzhao Gao, Hong Chen
conference: "Arxiv"
year: 2024
bibkey: wang2024retrieval
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.11050"}
tags: ['Responsible AI', 'Multimodal Models', 'Training Techniques', 'Tools', 'Reinforcement Learning', 'RAG', 'Merging', 'Prompting']
---
Understanding and addressing corner cases is essential for ensuring the safety and reliability of autonomous driving systems. Vision-language models (VLMs) play a crucial role in enhancing scenario comprehension, yet they face significant challenges, such as hallucination and insufficient real-world grounding, which compromise their performance in critical driving scenarios. In this work, RAC3, a novel framework designed to enhance the performance of VLMs in corner case comprehension, is proposed. RAC3 integrates a frequency-spatial fusion (FSF) image encoder, a cross-modal alignment training method for embedding models with hard and semi-hard negative mining, and a fast querying and retrieval pipeline based on K-Means clustering and hierarchical navigable small world (HNSW) indexing. A multimodal chain-of-thought (CoT) prompting strategy to guide analogical reasoning and reduce hallucinations during inference is introduced. Moreover, an update mechanism is integrated into RAC3 to ensure continual learning within the framework. Extensive experiments on the CODA and nuScenes datasets demonstrate that RAC3 significantly improves corner case comprehension across multiple downstream tasks. Compared to prior state-of-the-art methods, RAC3 achieves the highest final score of 74.46 on the CODA-LM benchmark and shows consistent performance gains when integrated with end-to-end frameworks like DriveLM. These results demonstrate the effectiveness of retrieval-augmented strategies and cross-modal alignment for safer and more interpretable autonomous driving.
