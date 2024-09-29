---
layout: publication
title: Lloco Learning Long Contexts Offline
authors: Tan Sijun, Li Xiuyu, Patil Shishir, Wu Ziyang, Zhang Tianjun, Keutzer Kurt, Gonzalez Joseph E., Popa Raluca Ada
conference: "Arxiv"
year: 2024
bibkey: tan2024learning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.07979"}
  - {name: "Code", url: "https://github.com/jeffreysijuntan/lloco"}
tags: ['Applications', 'Attention Mechanism', 'Fine Tuning', 'Has Code', 'Model Architecture', 'Transformer']
---
Processing long contexts remains a challenge for large language models (LLMs) due to the quadratic computational and memory overhead of the self45;attention mechanism and the substantial KV cache sizes during generation. We propose a novel approach to address this problem by learning contexts offline through context compression and in45;domain parameter45;efficient finetuning. Our method enables an LLM to create a concise representation of the original context and efficiently retrieve relevant information to answer questions accurately. We introduce LLoCO a technique that combines context compression retrieval and parameter45;efficient finetuning using LoRA. Our approach extends the effective context window of a 4k token LLaMA245;7B model to handle up to 128k tokens. We evaluate our approach on several long45;context question45;answering datasets demonstrating that LLoCO significantly outperforms in45;context learning while using 30× fewer tokens during inference. LLoCO achieves up to 7.62× speed45;up and substantially reduces the cost of long document question answering making it a promising solution for efficient long context processing. Our code is publicly available at https://github.com/jeffreysijuntan/lloco.
