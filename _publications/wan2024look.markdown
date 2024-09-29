---
layout: publication
title: LOOK45;M Look45;once Optimization In KV Cache For Efficient Multimodal Long45;context Inference
authors: Wan Zhongwei, Wu Ziang, Liu Che, Huang Jinfa, Zhu Zhihong, Jin Peng, Wang Longyue, Yuan Li
conference: "Arxiv"
year: 2024
bibkey: wan2024look
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.18139"}
tags: ['Attention Mechanism', 'Efficiency And Optimization', 'Merging', 'Model Architecture', 'Multimodal Models', 'Prompting']
---
Long45;context Multimodal Large Language Models (MLLMs) demand substantial computational resources for inference as the growth of their multimodal Key45;Value (KV) cache in response to increasing input lengths challenges memory and time efficiency. Unlike single45;modality LLMs that manage only textual contexts the KV cache of long45;context MLLMs includes representations from multiple images with temporal and spatial relationships and related textual contexts. The predominance of image tokens means traditional optimizations for LLMs KV caches are unsuitable for multimodal long45;context settings and no prior works have addressed this challenge. In this work we introduce LOOK45;M a pioneering fine45;tuning45;free approach that efficiently reduces the multimodal KV cache size while maintaining performance comparable to a full cache. We observe that during prompt prefill the model prioritizes more textual attention over image features and based on the multimodal interaction observation a new proposed text45;prior method is explored to compress the KV cache. Furthermore to mitigate the degradation of image contextual information we propose several compensatory strategies using KV pairs merging. LOOK45;M demonstrates that with a significant reduction in KV Cache memory usage such as reducing it by 8037; in some cases it not only achieves up to 1.5x faster decoding but also maintains or even enhances performance across a variety of long context multimodal tasks.
