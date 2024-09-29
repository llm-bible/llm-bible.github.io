---
layout: publication
title: Benchmarking Benchmark Leakage in Large Language Models
authors: Xu Ruijie, Wang Zengzhi, Fan Run-ze, Liu Pengfei
conference: "Arxiv"
year: 2024
bibkey: xu2024benchmarking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.18824"}
tags: ['Ethics And Bias', 'Prompting', 'RAG', 'Training Techniques']
---
Amid the expanding use of pre-training data the phenomenon of benchmark dataset leakage has become increasingly prominent exacerbated by opaque training processes and the often undisclosed inclusion of supervised data in contemporary Large Language Models (LLMs). This issue skews benchmark effectiveness and fosters potentially unfair comparisons impeding the fields healthy development. To address this we introduce a detection pipeline utilizing Perplexity and N-gram accuracy two simple and scalable metrics that gauge a models prediction precision on benchmark to identify potential data leakages. By analyzing 31 LLMs under the context of mathematical reasoning we reveal substantial instances of training even test set misuse resulting in potentially unfair comparisons. These findings prompt us to offer several recommendations regarding model documentation benchmark setup and future evaluations. Notably we propose the Benchmark Transparency Card to encourage clear documentation of benchmark utilization promoting transparency and healthy developments of LLMs. we have made our leaderboard pipeline implementation and model predictions publicly available fostering future research.
