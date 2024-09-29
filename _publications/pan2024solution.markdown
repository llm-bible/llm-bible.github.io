---
layout: publication
title: "The Solution For The AIGC Inference Performance Optimization Competition"
authors: Pan Sishun, Xu Haonan, Wan Zhonghua, Yang Yang
conference: "Arxiv"
year: 2024
bibkey: pan2024solution
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.04991"}
tags: ['Efficiency And Optimization', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Pruning', 'RAG', 'Tools', 'Transformer']
---
In recent years the rapid advancement of large-scale pre-trained language models based on transformer architectures has revolutionized natural language processing tasks. Among these ChatGPT has gained widespread popularity demonstrating human-level conversational abilities and attracting over 100 million monthly users by late 2022. Concurrently Baidus commercial deployment of the Ernie Wenxin model has significantly enhanced marketing effectiveness through AI-driven technologies. This paper focuses on optimizing high-performance inference for Ernie models emphasizing GPU acceleration and leveraging the Paddle inference framework. We employ techniques such as Faster Transformer for efficient model processing embedding layer pruning to reduce computational overhead and FP16 half-precision inference for enhanced computational efficiency. Additionally our approach integrates efficient data handling strategies using multi-process parallel processing to minimize latency. Experimental results demonstrate that our optimized solution achieves up to an 8.96x improvement in inference speed compared to standard methods while maintaining competitive performance.
