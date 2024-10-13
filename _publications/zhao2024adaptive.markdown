---
layout: publication
title: 'APT: Adaptive Pruning And Tuning Pretrained Language Models For Efficient Training And Inference'
authors: Zhao Bowen, Hajishirzi Hannaneh, Cao Qingqing
conference: "Arxiv"
year: 2024
bibkey: zhao2024adaptive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.12200"}
tags: ['BERT', 'Efficiency And Optimization', 'Fine Tuning', 'Model Architecture', 'Pretraining Methods', 'Pruning', 'Reinforcement Learning', 'Training Techniques']
---
Fine-tuning and inference with large Language Models (LM) are generally known
to be expensive. Parameter-efficient fine-tuning over pretrained LMs reduces
training memory by updating a small number of LM parameters but does not
improve inference efficiency. Structured pruning improves LM inference
efficiency by removing consistent parameter blocks, yet often increases
training memory and time. To improve both training and inference efficiency, we
introduce APT that adaptively prunes and tunes parameters for the LMs. At the
early stage of fine-tuning, APT dynamically adds salient tuning parameters for
fast and accurate convergence while discarding unimportant parameters for
efficiency. Compared to baselines, our experiments show that APT maintains up
to 98% task performance when pruning RoBERTa and T5 models with 40% parameters
left while keeping 86.4% LLaMA models' performance with 70% parameters
remained. Furthermore, APT speeds up LMs fine-tuning by up to 8x and reduces
large LMs memory training footprint by up to 70%.
