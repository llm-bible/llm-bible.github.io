---
layout: publication
title: 'Yuan 1.0: Large-scale Pre-trained Language Model In Zero-shot And Few-shot Learning'
authors: Wu Shaohua, Zhao Xudong, Yu Tong, Zhang Rongguo, Shen Chong, Liu Hongli, Li Feng, Zhu Hong, Luo Jiangang, Xu Liang, Zhang Xuanwei
conference: "Arxiv"
year: 2021
bibkey: wu2021yuan
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2110.04725"}
tags: ['Few Shot', 'GPT', 'Large Scale Training', 'Model Architecture', 'Training Techniques']
---
Recent work like GPT-3 has demonstrated excellent performance of Zero-Shot and Few-Shot learning on many natural language processing (NLP) tasks by scaling up model size, dataset size and the amount of computation. However, training a model like GPT-3 requires huge amount of computational resources which makes it challengeable to researchers. In this work, we propose a method that incorporates large-scale distributed training performance into model architecture design. With this method, Yuan 1.0, the current largest singleton language model with 245B parameters, achieves excellent performance on thousands GPUs during training, and the state-of-the-art results on NLP tasks. A data processing method is designed to efficiently filter massive amount of raw data. The current largest high-quality Chinese corpus with 5TB high quality texts is built based on this method. In addition, a calibration and label expansion method is proposed to improve the Zero-Shot and Few-Shot performance, and steady improvement is observed on the accuracy of various tasks. Yuan 1.0 presents strong capacity of natural language generation, and the generated articles are difficult to distinguish from the human-written ones.
