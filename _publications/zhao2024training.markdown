---
layout: publication
title: 'Longskywork: A Training Recipe For Efficiently Extending Context Length In Large Language Models'
authors: Liang Zhao, Tianwen Wei, Liang Zeng, Cheng Cheng, Liu Yang, Peng Cheng, Lijie Wang, Chenxia Li, Xuejie Wu, Bo Zhu, Yimeng Gan, Rui Hu, Shuicheng Yan, Han Fang, Yahui Zhou
conference: "Arxiv"
year: 2024
bibkey: zhao2024training
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.00605"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Language Modeling', 'Pretraining Methods', 'Fine-Tuning']
---
We introduce LongSkywork, a long-context Large Language Model (LLM) capable
of processing up to 200,000 tokens. We provide a training recipe for
efficiently extending context length of LLMs. We identify that the critical
element in enhancing long-context processing capability is to incorporate a
long-context SFT stage following the standard SFT stage. A mere 200 iterations
can convert the standard SFT model into a long-context model. To reduce the
effort in collecting and annotating data for long-context language modeling, we
develop two novel methods for creating synthetic data. These methods are
applied during the continual pretraining phase as well as the Supervised
Fine-Tuning (SFT) phase, greatly enhancing the training efficiency of our
long-context LLMs. Our findings suggest that synthetic long-context SFT data
can surpass the performance of data curated by humans to some extent.
LongSkywork achieves outstanding performance on a variety of long-context
benchmarks. In the Needle test, a benchmark for long-context information
retrieval, our models achieved perfect accuracy across multiple context spans.
Moreover, in realistic application scenarios, LongSkywork-13B demonstrates
performance on par with Claude2.1, the leading long-context model, underscoring
the effectiveness of our proposed methods.
