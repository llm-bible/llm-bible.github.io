---
layout: publication
title: 'Minos: A Multimodal Evaluation Model For Bidirectional Generation Between Image And Text'
authors: Junzhe Zhang, Huixuan Zhang, Xinyu Hu, Li Lin, Mingqi Gao, Shi Qiu, Xiaojun Wan
conference: "Arxiv"
year: 2025
bibkey: zhang2025multimodal
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.02494"}
tags: ['Fine-Tuning', 'Tools', 'GPT', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Multimodal Models']
---
Evaluation is important for multimodal generation tasks. With the rapid progress of MLLMs, there is growing interest in applying MLLMs to build general evaluation systems. However, existing work overlooks two aspects: (1) the development of evaluation capabilities for text-to-image (T2I) generation task, and (2) the incorporation of large-scale human evaluation data. In this paper, we introduce Minos-Corpus, a large-scale multimodal evaluation dataset that combines evaluation data from both human and GPT. The corpus contains evaluation data across both image-to-text(I2T) and T2I generation tasks. Based on this corpus, we propose Data Selection and Balance, Mix-SFT training methods, and apply DPO to develop Minos, a multimodal evaluation model built upon a 7B backbone. Minos achieves state-of-the-art (SoTA) performance among all open-source evaluation models of similar scale on the average of evaluation performance on all tasks, and outperforms all open-source and closed-source models on evaluation of T2I generation task. Extensive experiments demonstrate the importance of leveraging high-quality human evaluation data and jointly training on evaluation data from both I2T and T2I generation tasks.
