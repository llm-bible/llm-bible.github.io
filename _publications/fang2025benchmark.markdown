---
layout: publication
title: 'S2sbench: A Benchmark For Quantifying Intelligence Degradation In Speech-to-speech Large Language Models'
authors: Yuanbo Fang, Haoze Sun, Jun Liu, Tao Zhang, Zenan Zhou, Weipeng Chen, Xiaofen Xing, Xiangmin Xu
conference: "Arxiv"
year: 2025
bibkey: fang2025benchmark
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.14438"}
  - {name: "Code", url: "https://github.com/undobug/S2SBench"}
tags: ['Training Techniques', 'Has Code']
---
End-to-end speech large language models ((LLMs)) extend the capabilities of text-based models to directly process and generate audio tokens. However, this often leads to a decline in reasoning and generation performance compared to text input, a phenomenon referred to as intelligence degradation. To systematically evaluate this gap, we propose S2SBench, a benchmark designed to quantify performance degradation in Speech LLMs. It includes diagnostic datasets targeting sentence continuation and commonsense reasoning under audio input. We further introduce a pairwise evaluation protocol based on perplexity differences between plausible and implausible samples to measure degradation relative to text input. We apply S2SBench to analyze the training process of Baichuan-Audio, which further demonstrates the benchmark's effectiveness. All datasets and evaluation code are available at https://github.com/undobug/S2SBench.
