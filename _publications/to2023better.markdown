---
layout: publication
title: 'Better Language Models Of Code Through Self-improvement'
authors: To Hung Quoc, Bui Nghi D. Q., Guo Jin, Nguyen Tien N.
conference: "Arxiv"
year: 2023
bibkey: to2023better
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2304.01228"}
tags: ['Applications', 'Attention Mechanism', 'BERT', 'Fine Tuning', 'Model Architecture', 'Pretraining Methods', 'Tools', 'Training Techniques']
---
Pre-trained language models for code (PLMCs) have gained attention in recent research. These models are pre-trained on large-scale datasets using multi-modal objectives. However fine-tuning them requires extensive supervision and is limited by the size of the dataset provided. We aim to improve this issue by proposing a simple data augmentation framework. Our framework utilizes knowledge gained during the pre-training and fine-tuning stage to generate pseudo data which is then used as training data for the next step. We incorporate this framework into the state-of-the-art language models such as CodeT5 CodeBERT and UnixCoder. The results show that our framework significantly improves PLMCs performance in code-related sequence generation tasks such as code summarization and code generation in the CodeXGLUE benchmark.
