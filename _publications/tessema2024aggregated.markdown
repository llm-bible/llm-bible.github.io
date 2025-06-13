---
layout: publication
title: 'Unifiedcrawl: Aggregated Common Crawl For Affordable Adaptation Of Llms On Low-resource Languages'
authors: Bethel Melesse Tessema, Akhil Kedia, Tae-sun Chung
conference: "Arxiv"
year: 2024
bibkey: tessema2024aggregated
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.14343"}
  - {name: "Code", url: "https://github.com/bethelmelesse/unifiedcrawl"}
tags: ['Training Techniques', 'Few-Shot', 'Language Modeling', 'RAG', 'Pretraining Methods', 'Fine-Tuning', 'Has Code', 'Prompting']
---
Large language models (LLMs) under-perform on low-resource languages due to
limited training data. We present a method to efficiently collect text data for
low-resource languages from the entire Common Crawl corpus. Our approach,
UnifiedCrawl, filters and extracts common crawl using minimal compute
resources, yielding mono-lingual datasets much larger than previously available
sources. We demonstrate that leveraging this data to fine-tuning multilingual
LLMs via efficient adapter methods (QLoRA) significantly boosts performance on
the low-resource language, while minimizing VRAM usage. Our experiments show
large improvements in language modeling perplexity and an increase in few-shot
prompting scores. Our work and released source code provide an affordable
approach to improve LLMs for low-resource languages using consumer hardware.
Our source code is available here at
https://github.com/bethelmelesse/unifiedcrawl.
