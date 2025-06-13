---
layout: publication
title: 'An Early FIRST Reproduction And Improvements To Single-token Decoding For Fast Listwise Reranking'
authors: Zijian Chen, Ronak Pradeep, Jimmy Lin
conference: "Arxiv"
year: 2024
bibkey: chen2024early
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2411.05508'}
tags: ['Language Modeling', 'RAG', 'Security', 'Applications', 'Training Techniques', 'Fine-Tuning', 'Reinforcement Learning', 'Pre-Training', 'Pretraining Methods']
---
Recent advances have demonstrated that large language models (LLMs) excel as
listwise rerankers, but their high computational demands remain a barrier to
widespread adoption. Further, the traditional language modeling (LM) objective
is not ideally suited for reranking tasks. FIRST is a novel approach that
addresses these challenges by integrating a learning-to-rank objective and
leveraging the logits of only the first generated token, thereby significantly
reducing inference latency compared to traditional LLM rerankers. In this
study, we extend the evaluation of FIRST to the TREC Deep Learning datasets
(DL19-22), validating its robustness across diverse domains. We investigate the
influence of different first-stage retrievers on FIRST rerankers, observing
diminishing returns and patterns consistent with traditional LLM rerankers.
Through applying the FIRST objective to a broader range of backbone models, we
achieve effectiveness surpassing the original implementation. Our experiments
confirm that fast reranking with single-token logits does not compromise
out-of-domain reranking quality. To better quantify the computational savings
in the original study, we measure and compare latency to find a 21%-42% gain
across various models and benchmarks. Moreover, while LM training implicitly
improves zero-shot single-token reranking, our experiments also raise questions
about whether LM pre-training may hinder subsequent fine-tuning with the FIRST
objective. These findings pave the way for more efficient and effective
listwise reranking in future applications.
