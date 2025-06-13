---
layout: publication
title: 'Layerif: Estimating Layer Quality For Large Language Models Using Influence Functions'
authors: Hadi Askari, Shivanshu Gupta, Fei Wang, Anshuman Chhabra, Muhao Chen
conference: "Arxiv"
year: 2025
bibkey: askari2025estimating
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.23811'}
tags: ['RAG', 'Efficiency and Optimization', 'Applications', 'Model Architecture', 'Tools', 'Fine-Tuning', 'Training Techniques', 'Pruning', 'Reinforcement Learning']
---
Pretrained Large Language Models (LLMs) achieve strong performance across a wide range of tasks, yet exhibit substantial variability in the various layers' training quality with respect to specific downstream applications, limiting their downstream performance. It is therefore critical to estimate layer-wise training quality in a manner that accounts for both model architecture and training data. However, existing approaches predominantly rely on model-centric heuristics (such as spectral statistics, outlier detection, or uniform allocation) while overlooking the influence of data. To address these limitations, we propose LayerIF, a data-driven framework that leverages Influence Functions to quantify the training quality of individual layers in a principled and task-sensitive manner. By isolating each layer's gradients and measuring the sensitivity of the validation loss to training examples by computing layer-wise influences, we derive data-driven estimates of layer importance. Notably, our method produces task-specific layer importance estimates for the same LLM, revealing how layers specialize for different test-time evaluation tasks. We demonstrate the utility of our scores by leveraging them for two downstream applications: (a) expert allocation in LoRA-MoE architectures and (b) layer-wise sparsity distribution for LLM pruning. Experiments across multiple LLM architectures demonstrate that our model-agnostic, influence-guided allocation leads to consistent gains in task performance.
