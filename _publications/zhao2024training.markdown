---
layout: publication
title: Longskywork A Training Recipe For Efficiently Extending Context Length In Large Language Models
authors: Zhao Liang, Wei Tianwen, Zeng Liang, Cheng Cheng, Yang Liu, Cheng Peng, Wang Lijie, Li Chenxia, Wu Xuejie, Zhu Bo, Gan Yimeng, Hu Rui, Yan Shuicheng, Fang Han, Zhou Yahui
conference: "Arxiv"
year: 2024
bibkey: zhao2024training
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.00605"}
tags: ['Applications', 'Efficiency And Optimization', 'Fine Tuning', 'Language Modeling', 'Pretraining Methods', 'Training Techniques']
---
We introduce LongSkywork a long45;context Large Language Model (LLM) capable of processing up to 200000 tokens. We provide a training recipe for efficiently extending context length of LLMs. We identify that the critical element in enhancing long45;context processing capability is to incorporate a long45;context SFT stage following the standard SFT stage. A mere 200 iterations can convert the standard SFT model into a long45;context model. To reduce the effort in collecting and annotating data for long45;context language modeling we develop two novel methods for creating synthetic data. These methods are applied during the continual pretraining phase as well as the Supervised Fine45;Tuning (SFT) phase greatly enhancing the training efficiency of our long45;context LLMs. Our findings suggest that synthetic long45;context SFT data can surpass the performance of data curated by humans to some extent. LongSkywork achieves outstanding performance on a variety of long45;context benchmarks. In the Needle test a benchmark for long45;context information retrieval our models achieved perfect accuracy across multiple context spans. Moreover in realistic application scenarios LongSkywork45;13B demonstrates performance on par with Claude2.1 the leading long45;context model underscoring the effectiveness of our proposed methods.
