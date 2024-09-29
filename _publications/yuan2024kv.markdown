---
layout: publication
title: 'KV Cache Compression, But What Must We Give In Return? A Comprehensive Benchmark Of Long Context Capable Approaches'
authors: Yuan Jiayi Henry, Liu Hongyi Henry, Shaochen Henry, Zhong, Chuang Yu-neng, Li Songchen, Wang Guanchu, Le Duy, Jin Hongye, Chaudhary Vipin, Xu Zhaozhuo, Liu Zirui, Hu Xia
conference: "Arxiv"
year: 2024
bibkey: yuan2024kv
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.01527"}
  - {name: "Code", url: "https://github.com/henryzhongsc/longctx_bench"}
tags: ['Applications', 'Efficiency And Optimization', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Quantization', 'Transformer']
---
Long context capability is a crucial competency for large language models (LLMs) as it mitigates the human struggle to digest long-form texts. This capability enables complex task-solving scenarios such as book summarization code assistance and many more tasks that are traditionally manpower-intensive. However transformer-based LLMs face significant challenges with long context input due to the growing size of the KV cache and the intrinsic complexity of attending to extended inputs; where multiple schools of efficiency-driven approaches -- such as KV cache quantization token dropping prompt compression linear-time sequence models and hybrid architectures -- have been proposed to produce efficient yet long context-capable models. Despite these advancements no existing work has comprehensively benchmarked these methods in a reasonably aligned environment. In this work we fill this gap by providing a taxonomy of current methods and evaluating 10+ state-of-the-art approaches across seven categories of long context tasks. Our work reveals numerous previously unknown phenomena and offers insights -- as well as a friendly workbench -- for the future development of long context-capable LLMs. The source code will be available at https://github.com/henryzhongsc/longctx\_bench"
