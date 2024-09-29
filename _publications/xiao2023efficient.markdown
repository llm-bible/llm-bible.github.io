---
layout: publication
title: Efficient Streaming Language Models With Attention Sinks
authors: Xiao Guangxuan, Tian Yuandong, Chen Beidi, Han Song, Lewis Mike
conference: "Arxiv"
year: 2023
bibkey: xiao2023efficient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.17453"}
  - {name: "Code", url: "https://github.com/mit&#45;han&#45;lab/streaming&#45;llm"}
tags: ['Applications', 'Attention Mechanism', 'Has Code', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'Tools', 'Training Techniques']
---
Deploying Large Language Models (LLMs) in streaming applications such as multi45;round dialogue where long interactions are expected is urgently needed but poses two major challenges. Firstly during the decoding stage caching previous tokens Key and Value states (KV) consumes extensive memory. Secondly popular LLMs cannot generalize to longer texts than the training sequence length. Window attention where only the most recent KVs are cached is a natural approach 45;45; but we show that it fails when the text length surpasses the cache size. We observe an interesting phenomenon namely attention sink that keeping the KV of initial tokens will largely recover the performance of window attention. In this paper we first demonstrate that the emergence of attention sink is due to the strong attention scores towards initial tokens as a sink even if they are not semantically important. Based on the above analysis we introduce StreamingLLM an efficient framework that enables LLMs trained with a finite length attention window to generalize to infinite sequence lengths without any fine45;tuning. We show that StreamingLLM can enable Llama45;2 MPT Falcon and Pythia to perform stable and efficient language modeling with up to 4 million tokens and more. In addition we discover that adding a placeholder token as a dedicated attention sink during pre45;training can further improve streaming deployment. In streaming settings StreamingLLM outperforms the sliding window recomputation baseline by up to 22.2x speedup. Code and datasets are provided at https://github.com/mit&#45;han&#45;lab/streaming&#45;llm.
