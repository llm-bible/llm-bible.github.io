---
layout: publication
title: CORM\: Cache Optimization With Recent Message For Large Language Model Inference
authors: Dai Jincheng, Huang Zhuowei, Jiang Haiyun, Chen Chen, Cai Deng, Bi Wei, Shi Shuming
conference: "Arxiv"
year: 2024
bibkey: dai2024cache
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.15949"}
tags: ['Attention Mechanism', 'Efficiency And Optimization', 'Fine Tuning', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
Large Language Models (LLMs) despite their remarkable performance across a wide range of tasks necessitate substantial GPU memory and consume significant computational resources. Beyond the memory taken up by model weights the memory used by the KV cache rises linearly with sequence length becoming a primary bottleneck for inference. In this paper we introduce an innovative method for optimizing the KV cache which considerably minimizes its memory footprint. Upon thorough investigation we discover that in most Transformer models (i) there is a striking similarity between adjacent tokens query vectors and (ii) the attention calculation of the current query can rely exclusively on the attention information of a small fraction of preceding queries. Based on these observations we present CORM a KV cache eviction policy that dynamically retains essential key-value pairs for inference without the need for model fine-tuning. Our validation shows that CORM reduces the inference memory usage of KV cache by up to 7037; with negligible performance degradation across six tasks in LongBench. Furthermore we demonstrate that CORM is compatible with GQA for further compression rate.
