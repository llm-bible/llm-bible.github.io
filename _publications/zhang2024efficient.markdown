---
layout: publication
title: 'Efficient Bilinear Attention-based Fusion For Medical Visual Question Answering'
authors: Zhilin Zhang, Jie Wang, Zhanghao Qin, Ruiqi Zhu, Xiaoliang Gong
conference: "Arxiv"
year: 2024
bibkey: zhang2024efficient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.21000"}
tags: ['Efficiency and Optimization', 'Model Architecture', 'Multimodal Models', 'Reinforcement Learning', 'Merging', 'Pretraining Methods', 'Transformer', 'Applications', 'Attention Mechanism']
---
Medical Visual Question Answering (MedVQA) has attracted growing interest at the intersection of medical image understanding and natural language processing for clinical applications. By interpreting medical images and providing precise answers to relevant clinical inquiries, MedVQA has the potential to support diagnostic decision-making and reduce workload across various fields like radiology. While recent approaches rely heavily on unified large pre-trained Visual-Language Models, research on more efficient fusion mechanisms remains relatively limited in this domain. In this paper, we introduce a fusion model, OMniBAN, that integrates Orthogonality loss, Multi-head attention, and a Bilinear Attention Network to achieve high computational efficiency as well as solid performance. We conduct comprehensive experiments and demonstrate how bilinear attention fusion can approximate the performance of larger fusion models like cross-modal Transformer. Our results show that OMniBAN requires fewer parameters (approximately 2/3 of Transformer-based Co-Attention) and substantially lower FLOPs (approximately 1/4), while achieving comparable overall performance and even slight improvements on closed-ended questions on two key MedVQA benchmarks. This balance between efficiency and accuracy suggests that OMniBAN could be a viable option for real-world medical image question answering, where computational resources are often constrained.
