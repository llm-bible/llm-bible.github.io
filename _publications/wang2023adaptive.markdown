---
layout: publication
title: Smarttrim&#58; Adaptive Tokens And Attention Pruning For Efficient Vision-language Models
authors: Wang Zekun, Chen Jingchang, Zhou Wangchunshu, Zhu Haichao, Liang Jiafeng, Shan Liping, Liu Ming, Xu Dongliang, Yang Qing, Qin Bing
conference: "Arxiv"
year: 2023
bibkey: wang2023adaptive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.15033"}
  - {name: "Code", url: "https://github.com/kugwzk/SmartTrim"}
tags: ['Applications', 'Attention Mechanism', 'Distillation', 'Efficiency And Optimization', 'Has Code', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'Pruning', 'Reinforcement Learning', 'Tools', 'Transformer']
---
Despite achieving remarkable performance on various vision-language tasks Transformer-based Vision-Language Models (VLMs) suffer from redundancy in inputs and parameters significantly hampering their efficiency in real-world applications. Moreover the degree of redundancy in token representations and model parameters such as attention heads varies significantly for different inputs. In light of the challenges we propose SmartTrim an adaptive acceleration framework for VLMs which adjusts the computational overhead per instance. Specifically we integrate lightweight modules into the original backbone to identify and prune redundant token representations and attention heads within each layer. Furthermore we devise a self-distillation strategy to enhance the consistency between the predictions of the pruned model and its fully-capacity counterpart. Experimental results across various vision-language tasks consistently demonstrate that SmartTrim accelerates the original model by 2-3 times with minimal performance degradation highlighting the effectiveness and efficiency compared to previous approaches. Code will be available at https://github.com/kugwzk/SmartTrim."
