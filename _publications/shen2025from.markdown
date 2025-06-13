---
layout: publication
title: 'From Unaligned To Aligned: Scaling Multilingual Llms With Multi-way Parallel Corpora'
authors: Yingli Shen, Wen Lai, Shuo Wang, Kangyang Luo, Alexander Fraser, Maosong Sun
conference: "Arxiv"
year: 2025
bibkey: shen2025from
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.14045"}
tags: ['Pretraining Methods', 'RAG', 'Training Techniques']
---
Continued pretraining and instruction tuning on large-scale multilingual data have proven to be effective in scaling large language models (LLMs) to low-resource languages. However, the unaligned nature of such data limits its ability to effectively capture cross-lingual semantics. In contrast, multi-way parallel data, where identical content is aligned across multiple languages, provides stronger cross-lingual consistency and offers greater potential for improving multilingual performance. In this paper, we introduce a large-scale, high-quality multi-way parallel corpus, TED2025, based on TED Talks. The corpus spans 113 languages, with up to 50 languages aligned in parallel, ensuring extensive multilingual coverage. Using this dataset, we investigate best practices for leveraging multi-way parallel data to enhance LLMs, including strategies for continued pretraining, instruction tuning, and the analysis of key influencing factors. Experiments on six multilingual benchmarks show that models trained on multiway parallel data consistently outperform those trained on unaligned multilingual data.
