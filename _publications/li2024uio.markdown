---
layout: publication
title: Uio-llms Unbiased Incremental Optimization For Long-context Llms
authors: Li Wenhao, Lin Mingbao, Zhong Yunshan, Yan Shuicheng, Ji Rongrong
conference: "Arxiv"
year: 2024
bibkey: li2024uio
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.18173"}
tags: ['Efficiency And Optimization', 'Ethics And Bias', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Tools', 'Training Techniques', 'Transformer']
---
Managing long texts is challenging for large language models (LLMs) due to limited context window sizes. This study introduces UIO-LLMs an unbiased incremental optimization approach for memory-enhanced transformers under long-context settings. We initially conceptualize the process as a streamlined encoder-decoder framework where the weights-shared encoder and decoder respectively encapsulate a context segment into memories and leverage these memories to predict outputs of the subsequent segment. Subsequently by treating our memory-enhanced transformers as fully-connected recurrent neural networks (RNNs) we refine the training process using the Truncated Backpropagation Through Time (TBPTT) algorithm which incorporates innovative incremental optimization techniques. These techniques not only diminish time complexity but also address the bias in gradient computation through an unbiased optimization process. UIO-LLMs successfully handle long context such as extending the context window of Llama2-7b-chat from 4K to 100K tokens with minimal 237; additional parameters while keeping the inference cost nearly linear as context length increases.
