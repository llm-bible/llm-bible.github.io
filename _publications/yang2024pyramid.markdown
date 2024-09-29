---
layout: publication
title: Pyramidinfer Pyramid KV Cache Compression For High45;throughput LLM Inference
authors: Yang Dongjie, Han Xiaodong, Gao Yan, Hu Yao, Zhang Shilin, Zhao Hai
conference: "Arxiv"
year: 2024
bibkey: yang2024pyramid
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.12532"}
tags: ['Applications', 'Attention Mechanism', 'Efficiency And Optimization', 'Model Architecture', 'Pruning']
---
Large Language Models (LLMs) have shown remarkable comprehension abilities but face challenges in GPU memory usage during inference hindering their scalability for real45;time applications like chatbots. To accelerate inference we store computed keys and values (KV cache) in the GPU memory. Existing methods study the KV cache compression to reduce memory by pruning the pre45;computed KV cache. However they neglect the inter45;layer dependency between layers and huge memory consumption in pre45;computation. To explore these deficiencies we find that the number of crucial keys and values that influence future generations decreases layer by layer and we can extract them by the consistency in attention weights. Based on the findings we propose PyramidInfer a method that compresses the KV cache by layer45;wise retaining crucial context. PyramidInfer saves significant memory by computing fewer keys and values without sacrificing performance. Experimental results show PyramidInfer improves 2.2x throughput compared to Accelerate with over 5437; GPU memory reduction in KV cache.
