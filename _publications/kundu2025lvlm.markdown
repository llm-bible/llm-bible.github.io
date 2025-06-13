---
layout: publication
title: 'Lvlm-compress-bench: Benchmarking The Broader Impact Of Large Vision-language Model Compression'
authors: Souvik Kundu, Anahita Bhiwandiwalla, Sungduk Yu, Phillip Howard, Tiep Le, Sharath Nittur Sridhar, David Cobbley, Hao Kang, Vasudev Lal
conference: "Arxiv"
year: 2025
bibkey: kundu2025lvlm
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.04982'}
  - {name: "Code", url: 'https://github.com/opengear-project/LVLM-compress-bench'}
tags: ['Has Code', 'Language Modeling', 'RAG', 'Efficiency and Optimization', 'GPT', 'Tools', 'Quantization', 'Applications', 'Multimodal Models', 'Reinforcement Learning', 'Ethics and Bias', 'Pretraining Methods']
---
Despite recent efforts in understanding the compression impact on large
language models (LLMs) in terms of their downstream task performance and
trustworthiness on relatively simpler uni-modal benchmarks (for example,
question answering, common sense reasoning), their detailed study on
multi-modal Large Vision-Language Models (LVLMs) is yet to be unveiled. Towards
mitigating this gap, we present LVLM-Compress-Bench, a framework to first
thoroughly study the broad impact of compression on the generative performance
of LVLMs with multi-modal input driven tasks. In specific, we consider two
major classes of compression for autoregressive models, namely KV cache and
weight compression, for the dynamically growing intermediate cache and static
weights, respectively.
  We use four LVLM variants of the popular LLaVA framework to present our
analysis via integrating various state-of-the-art KV and weight compression
methods including uniform, outlier-reduced, and group quantization for the KV
cache and weights. With this framework we demonstrate on ten different
multi-modal datasets with different capabilities including recognition,
knowledge, language generation, spatial awareness, visual reasoning,
hallucination and visual illusion identification, toxicity, stereotypes and
bias. In specific, our framework demonstrates the compression impact on both
general and ethically critical metrics leveraging a combination of real world
and synthetic datasets to encompass diverse societal intersectional attributes.
Extensive experimental evaluations yield diverse and intriguing observations on
the behavior of LVLMs at different quantization budget of KV and weights, in
both maintaining and losing performance as compared to the baseline model with
FP16 data format.
  Code will be open-sourced at
https://github.com/opengear-project/LVLM-compress-bench.
