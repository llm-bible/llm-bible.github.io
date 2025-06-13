---
layout: publication
title: 'Rustevo^2: An Evolving Benchmark For API Evolution In Llm-based Rust Code Generation'
authors: Linxi Liang, Jing Gong, Mingwei Liu, Chong Wang, Guangsheng Ou, Yanlin Wang, Xin Peng, Zibin Zheng
conference: "Arxiv"
year: 2025
bibkey: liang2025evolving
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.16922'}
  - {name: "Code", url: 'https://github.com/SYSUSELab/RustEvo'}
tags: ['Has Code', 'RAG', 'Training Techniques', 'Applications', 'Tools', 'Reinforcement Learning']
---
Large Language Models (LLMs) have become pivotal tools for automating code
generation in software development. However, these models face significant
challenges in producing version-aware code for rapidly evolving languages like
Rust, where frequent Application Programming Interfaces (API) changes across
versions lead to compatibility issues and correctness errors. Existing
benchmarks lack systematic evaluation of how models navigate API transitions,
relying on labor-intensive manual curation and offering limited
version-specific insights. To address this gap, we present RustEvo, a novel
framework for constructing dynamic benchmarks that evaluate the ability of LLMs
to adapt to evolving Rust APIs. RustEvo automates dataset creation by
synthesizing 588 API changes (380 from Rust standard libraries, 208 from 15
third-party crates) into programming tasks mirroring real-world challenges.
These tasks cover four API evolution categories: Stabilizations, Signature
Changes, Behavioral Changes, and Deprecations, reflecting their actual
distribution in the Rust ecosystem.
  Experiments on state-of-the-art (SOTA) LLMs reveal significant performance
variations: models achieve a 65.8% average success rate on stabilized APIs but
only 38.0% on behavioral changes, highlighting difficulties in detecting
semantic shifts without signature alterations. Knowledge cutoff dates strongly
influence performance, with models scoring 56.1% on before-cutoff APIs versus
32.5% on after-cutoff tasks. Retrieval-Augmented Generation (RAG) mitigates
this gap, improving success rates by 13.5% on average for APIs released after
model training. Our findings underscore the necessity of our evolution-aware
benchmarks to advance the adaptability of LLMs in fast-paced software
ecosystems. The framework and the benchmarks are publicly released at
https://github.com/SYSUSELab/RustEvo.
