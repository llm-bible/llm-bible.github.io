---
layout: publication
title: 'The Lottery LLM Hypothesis, Rethinking What Abilities Should LLM Compression Preserve?'
authors: Zhenheng Tang, Xiang Liu, Qian Wang, Peijie Dong, Bingsheng He, Xiaowen Chu, Bo Li
conference: "Arxiv"
year: 2025
bibkey: tang2025lottery
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.17535'}
tags: ['Attention Mechanism', 'RAG', 'Model Architecture', 'Tools', 'Survey Paper', 'Reinforcement Learning']
---
Motivated by reducing the computational and storage costs of LLMs, model
compression and KV cache compression have attracted much attention from
researchers. However, current methods predominantly emphasize maintaining the
performance of compressed LLMs, as measured by perplexity or simple accuracy on
tasks of common sense knowledge QA and basic arithmetic reasoning. In this
blog, we present a brief review of recent advancements in LLMs related to
retrieval-augmented generation, multi-step reasoning, external tools, and
computational expressivity, all of which substantially enhance LLM performance.
Then, we propose a lottery LLM hypothesis suggesting that for a given LLM and
task, there exists a smaller lottery LLM capable of producing the same
performance as the original LLM with the assistance of multi-step reasoning and
external tools. Based on the review of current progress in LLMs, we discuss and
summarize the essential capabilities that the lottery LLM and KV cache
compression must possess, which are currently overlooked in existing methods.
