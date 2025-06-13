---
layout: publication
title: 'Speculative Decoding For Verilog: Speed And Quality, All In One'
authors: Changran Xu, Yi Liu, Yunhao Zhou, Shan Huang, Ningyi Xu, Qiang Xu
conference: "Arxiv"
year: 2025
bibkey: xu2025speculative
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.14153"}
tags: ['Tools', 'Applications', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Tokenization']
---
The rapid advancement of large language models (LLMs) has revolutionized code
generation tasks across various programming languages. However, the unique
characteristics of programming languages, particularly those like Verilog with
specific syntax and lower representation in training datasets, pose significant
challenges for conventional tokenization and decoding approaches. In this
paper, we introduce a novel application of speculative decoding for Verilog
code generation, showing that it can improve both inference speed and output
quality, effectively achieving speed and quality all in one. Unlike standard
LLM tokenization schemes, which often fragment meaningful code structures, our
approach aligns decoding stops with syntactically significant tokens, making it
easier for models to learn the token distribution. This refinement addresses
inherent tokenization issues and enhances the model's ability to capture
Verilog's logical constructs more effectively. Our experimental results show
that our method achieves up to a 5.05x speedup in Verilog code generation and
increases pass@10 functional accuracy on RTLLM by up to 17.19% compared to
conventional training strategies. These findings highlight speculative decoding
as a promising approach to bridge the quality gap in code generation for
specialized programming languages.
