---
layout: publication
title: 'Not All Heads Matter: A Head-level KV Cache Compression Method With Integrated Retrieval And Reasoning'
authors: Yu Fu, Zefan Cai, Abedelkadir Asi, Wayne Xiong, Yue Dong, Wen Xiao
conference: "Arxiv"
year: 2024
bibkey: fu2024not
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.19258"}
  - {name: "Code", url: "https://github.com/FYYFU/HeadKV"}
tags: ['Tools', 'Efficiency and Optimization', 'Applications', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Language Modeling', 'Attention Mechanism', 'Has Code']
---
Key-Value (KV) caching is a common technique to enhance the computational
efficiency of Large Language Models (LLMs), but its memory overhead grows
rapidly with input length. Prior work has shown that not all tokens are equally
important for text generation, proposing layer-level KV cache compression to
selectively retain key information. Recognizing the distinct roles of attention
heads in generation, we propose HeadKV, a head-level KV cache compression
method, and HeadKV-R2, which leverages a novel contextual reasoning ability
estimation for compression. Our approach operates at the level of individual
heads, estimating their importance for contextual QA tasks that require both
retrieval and reasoning capabilities. Extensive experiments across diverse
benchmarks (LongBench, LooGLE), model architectures (e.g., Llama-3-8B-Instruct,
Mistral-7B-Instruct), and long-context abilities tests demonstrate that our
head-level KV cache compression significantly outperforms strong baselines,
particularly in low-resource settings (KV size = 64 & 128). Notably, our method
retains just 1.5% of the KV cache while achieving 97% of the performance of the
full KV cache on the contextual question answering benchmark.Codes are
available at https://github.com/FYYFU/HeadKV
