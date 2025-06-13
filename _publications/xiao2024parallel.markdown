---
layout: publication
title: 'Parallelspec: Parallel Drafter For Efficient Speculative Decoding'
authors: Zilin Xiao, Hongming Zhang, Tao Ge, Siru Ouyang, Vicente Ordonez, Dong Yu
conference: "Arxiv"
year: 2024
bibkey: xiao2024parallel
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.05589"}
tags: ['Language Modeling', 'Training Techniques', 'Tools', 'RAG']
---
Speculative decoding has proven to be an efficient solution to large language
model (LLM) inference, where the small drafter predicts future tokens at a low
cost, and the target model is leveraged to verify them in parallel. However,
most existing works still draft tokens auto-regressively to maintain sequential
dependency in language modeling, which we consider a huge computational burden
in speculative decoding. We present ParallelSpec, an alternative to
auto-regressive drafting strategies in state-of-the-art speculative decoding
approaches. In contrast to auto-regressive drafting in the speculative stage,
we train a parallel drafter to serve as an efficient speculative model.
ParallelSpec learns to efficiently predict multiple future tokens in parallel
using a single model, and it can be integrated into any speculative decoding
framework that requires aligning the output distributions of the drafter and
the target model with minimal training cost. Experimental results show that
ParallelSpec accelerates baseline methods in latency up to 62% on text
generation benchmarks from different domains, and it achieves 2.84X overall
speedup on the Llama-2-13B model using third-party evaluation criteria.
