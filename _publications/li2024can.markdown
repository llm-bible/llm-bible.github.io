---
layout: publication
title: 'Can Graph Neural Networks Learn Language With Extremely Weak Text Supervision?'
authors: Zihao Li, Lecheng Zheng, Bowen Jin, Dongqi Fu, Baoyu Jing, Yikun Ban, Jingrui He, Jiawei Han
conference: "Arxiv"
year: 2024
bibkey: li2024can
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.08174"}
  - {name: "Code", url: "https://github.com/Violet24K/Morpher"}
tags: ['Pre-Training', 'Training Techniques', 'Has Code', 'Few-Shot', 'Multimodal Models', 'Prompting']
---
While great success has been achieved in building vision models with Contrastive Language-Image Pre-training (CLIP) over internet-scale image-text pairs, building transferable Graph Neural Networks (GNNs) with CLIP pipeline is challenging because of the scarcity of labeled data and text supervision, different levels of downstream tasks, and the conceptual gaps between domains. In this work, to address these issues, we propose a multi-modal prompt learning paradigm to effectively adapt pre-trained GNN to downstream tasks and data, given only a few semantically labeled samples, each with extremely weak text supervision. Our new paradigm embeds the graphs directly in the same space as the Large Language Models (LLMs) by learning both graph prompts and text prompts simultaneously. We demonstrate the superior performance of our paradigm in few-shot, multi-task-level, and cross-domain settings. Moreover, we build the first CLIP-style zero-shot classification prototype that can generalize GNNs to unseen classes with extremely weak text supervision. The code is available at https://github.com/Violet24K/Morpher.
