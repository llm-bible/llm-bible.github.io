---
layout: publication
title: Kv45;runahead Scalable Causal LLM Inference By Parallel Key45;value Cache Generation
authors: Cho Minsik, Rastegari Mohammad, Naik Devang
conference: "Arxiv"
year: 2024
bibkey: cho2024kv
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.05329"}
tags: ['Applications', 'Attention Mechanism', 'Large Scale Training', 'Model Architecture', 'Prompting', 'RAG']
---
Large Language Model or LLM inference has two phases the prompt (or prefill) phase to output the first token and the extension (or decoding) phase to the generate subsequent tokens. In this work we propose an efficient parallelization scheme KV45;Runahead to accelerate the prompt phase. The key observation is that the extension phase generates tokens faster than the prompt phase because of key45;value cache (KV45;cache). Hence KV45;Runahead parallelizes the prompt phase by orchestrating multiple processes to populate the KV45;cache and minimizes the time45;to45;first45;token (TTFT). Dual45;purposing the KV45;cache scheme has two main benefits. First since KV45;cache is designed to leverage the causal attention map we minimize computation and computation automatically. Second since it already exists for the extension phase KV45;Runahead is easy to implement. We further propose context45;level load45;balancing to handle uneven KV45;cache generation (due to the causal attention) and to optimize TTFT. Compared with an existing parallelization scheme such as tensor or sequential parallelization where keys and values are locally generated and exchanged via all45;gather collectives our experimental results demonstrate that KV45;Runahead can offer over 1.4x and 1.6x speedups for Llama 7B and Falcon 7B respectively.
