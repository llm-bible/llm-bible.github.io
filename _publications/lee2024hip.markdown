---
layout: publication
title: 'Hip Attention: Sparse Sub-quadratic Attention With Hierarchical Attention Pruning'
authors: Lee Heejun, Park Geon, Lee Youngwan, Kim Jina, Jeong Wonyoung, Jeon Myeongjae, Hwang Sung Ju
conference: "Arxiv"
year: 2024
bibkey: lee2024hip
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.09827"}
tags: ['Applications', 'Attention Mechanism', 'Efficiency And Optimization', 'Model Architecture', 'Prompting', 'Pruning', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
In modern large language models (LLMs) increasing sequence lengths is a crucial challenge for enhancing their comprehension and coherence in handling complex tasks such as multi-modal question answering. However handling long context sequences with LLMs is prohibitively costly due to the conventional attention mechanisms quadratic time and space complexity and the context window size is limited by the GPU memory. Although recent works have proposed linear and sparse attention mechanisms to address this issue their real-world applicability is often limited by the need to re-train pre-trained models. In response we propose a novel approach Hierarchically Pruned Attention (HiP) which simultaneously reduces the training and inference time complexity from O(T^2) to O(T (log) T) and the space complexity from O(T^2) to O(T). To this end we devise a dynamic sparse attention mechanism that generates an attention mask through a novel tree-search-like algorithm for a given query on the fly. HiP is training-free as it only utilizes the pre-trained attention scores to spot the positions of the top-k most significant elements for each query. Moreover it ensures that no token is overlooked unlike the sliding window-based sub-quadratic attention methods such as StreamingLLM. Extensive experiments on diverse real-world benchmarks demonstrate that HiP significantly reduces prompt (i.e. prefill) and decoding latency and memory usage while maintaining high generation performance with little or no degradation. As HiP allows pretrained LLMs to scale to millions of tokens on commodity GPUs with no additional engineering due to its easy plug-and-play deployment we believe that our work will have a large practical impact opening up the possibility to many long-context LLM applications previously infeasible.
