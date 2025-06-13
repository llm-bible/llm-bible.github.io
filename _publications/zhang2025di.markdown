---
layout: publication
title: 'DI-BENCH: Benchmarking Large Language Models On Dependency Inference With Testable Repositories At Scale'
authors: Linghao Zhang, Junhao Wang, Shilin He, Chaoyun Zhang, Yu Kang, Bowen Li, Jiaheng Wen, Chengxing Xie, Maoquan Wang, Yufan Huang, Elsie Nallipogu, Qingwei Lin, Yingnong Dang, Saravan Rajmohan, Dongmei Zhang, Qi Zhang
conference: "Arxiv"
year: 2025
bibkey: zhang2025di
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2501.13699'}
tags: ['Tools']
---
Large Language Models have advanced automated software development, however,
it remains a challenge to correctly infer dependencies, namely, identifying the
internal components and external packages required for a repository to
successfully run. Existing studies highlight that dependency-related issues
cause over 40% of observed runtime errors on the generated repository. To
address this, we introduce DI-BENCH, a large-scale benchmark and evaluation
framework specifically designed to assess LLMs' capability on dependency
inference. The benchmark features 581 repositories with testing environments
across Python, C#, Rust, and JavaScript. Extensive experiments with textual and
execution-based metrics reveal that the current best-performing model achieves
only a 42.9% execution pass rate, indicating significant room for improvement.
DI-BENCH establishes a new viewpoint for evaluating LLM performance on
repositories, paving the way for more robust end-to-end software synthesis.
