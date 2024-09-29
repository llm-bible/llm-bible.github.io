---
layout: publication
title: 'Training-free Exponential Extension Of Sliding Window Context With Cascading KV Cache'
authors: Willette Jeffrey, Lee Heejun, Lee Youngwan, Jeon Myeongjae, Hwang Sung Ju
conference: "Arxiv"
year: 2024
bibkey: willette2024training
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.17808"}
tags: ['Applications', 'Few Shot', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
The context window within a transformer provides a form of active memory for the current task which can be useful for few-shot learning and conditional generation both which depend heavily on previous context tokens. However as the context length grows the computational cost increases quadratically. Recent works have shown that saving a few initial tokens along with a fixed-sized sliding window leads to stable streaming generation with linear complexity in transformer-based Large Language Models (LLMs). However they make suboptimal use of the fixed window by naively evicting all tokens unconditionally from the key-value (KV) cache once they reach the end of the window resulting in tokens being forgotten and no longer able to affect subsequent predictions. To overcome this limitation we propose a novel mechanism for storing longer sliding window contexts with the same total cache size by keeping separate cascading sub-cache buffers whereby each subsequent buffer conditionally accepts a fraction of the relatively more important tokens evicted from the previous buffer. Our method results in a dynamic KV cache that can store tokens from the more distant past than a fixed static sliding window approach. Our experiments show improvements of 5.637; on long context generation (LongBench) 1.237; in streaming perplexity (PG19) and 0.637; in language understanding (MMLU STEM) using LLMs given the same fixed cache size. Additionally we provide an efficient implementation that improves the KV cache latency from 1.33ms per caching operation to 0.54ms a 5937; speedup over previous work.
