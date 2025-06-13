---
layout: publication
title: 'Writingbench: A Comprehensive Benchmark For Generative Writing'
authors: Yuning Wu, Jiahao Mei, Ming Yan, Chenliang Li, Shaopeng Lai, Yuran Ren, Zijia Wang, Ji Zhang, Mengyue Wu, Qin Jin, Fei Huang
conference: "Arxiv"
year: 2025
bibkey: wu2025comprehensive
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.05244'}
tags: ['Language Modeling', 'Applications', 'Tools']
---
Recent advancements in large language models (LLMs) have significantly
enhanced text generation capabilities, yet evaluating their performance in
generative writing remains a challenge. Existing benchmarks primarily focus on
generic text generation or limited in writing tasks, failing to capture the
diverse requirements of high-quality written contents across various domains.
To bridge this gap, we present WritingBench, a comprehensive benchmark designed
to evaluate LLMs across 6 core writing domains and 100 subdomains, encompassing
creative, persuasive, informative, and technical writing. We further propose a
query-dependent evaluation framework that empowers LLMs to dynamically generate
instance-specific assessment criteria. This framework is complemented by a
fine-tuned critic model for criteria-aware scoring, enabling evaluations in
style, format and length. The framework's validity is further demonstrated by
its data curation capability, which enables 7B-parameter models to approach
state-of-the-art (SOTA) performance. We open-source the benchmark, along with
evaluation tools and modular framework components, to advance the development
of LLMs in writing.
