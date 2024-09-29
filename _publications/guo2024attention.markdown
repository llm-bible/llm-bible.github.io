---
layout: publication
title: Attention Score Is Not All You Need For Token Importance Indicator In KV Cache Reduction Value Also Matters
authors: Guo Zhiyu, Kamigaito Hidetaka, Watanabe Taro
conference: "Arxiv"
year: 2024
bibkey: guo2024attention
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.12335"}
tags: ['Applications', 'Attention Mechanism', 'Efficiency And Optimization', 'Model Architecture', 'Pruning']
---
Scaling the context size of large language models (LLMs) enables them to perform various new tasks e.g. book summarization. However the memory cost of the Key and Value (KV) cache in attention significantly limits the practical applications of LLMs. Recent works have explored token pruning for KV cache reduction in LLMs relying solely on attention scores as a token importance indicator. However our investigation into value vector norms revealed a notably non45;uniform pattern questioning their reliance only on attention scores. Inspired by this we propose a new method Value45;Aware Token Pruning (VATP) which uses both attention scores and the ell95;123;1125; norm of value vectors to evaluate token importance. Extensive experiments on LLaMA245;7B45;chat and Vicuna45;v1.545;7B across 16 LongBench tasks demonstrate VATPs superior performance.
