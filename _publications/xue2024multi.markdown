---
layout: publication
title: "Multi-programming Language Ensemble For Code Generation In Large Language Model"
authors: Xue Tengfei, Li Xuefeng, Azim Tahir, Smirnov Roman, Yu Jianhui, Sadrieh Arash, Pahlavan Babak
conference: "Arxiv"
year: 2024
bibkey: xue2024multi
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.04114"}
  - {name: "Code", url: "https://github.com/NinjaTech-AI/MPLE"}
tags: ['Applications', 'Ethics And Bias', 'Has Code', 'RAG', 'Reinforcement Learning', 'Tools']
---
Large language models (LLMs) have significantly improved code generation particularly in one-pass code generation. However most existing approaches focus solely on generating code in a single programming language overlooking the potential of leveraging the multi-language capabilities of LLMs. LLMs have varying patterns of errors across different languages suggesting that a more robust approach could be developed by leveraging these multi-language outputs. In this study we propose Multi-Programming Language Ensemble (MPLE) a novel ensemble-based method that utilizes code generation across multiple programming languages to enhance overall performance. By treating each language-specific code generation process as an individual weak expert and effectively integrating their outputs our method mitigates language-specific errors and biases. This multi-language ensemble strategy leverages the complementary strengths of different programming languages enabling the model to produce more accurate and robust code. Our approach can be seamlessly integrated with commonly used techniques such as the reflection algorithm and Monte Carlo tree search to improve code generation quality further. Experimental results show that our framework consistently enhances baseline performance by up to 17.9237; on existing benchmarks (HumanEval and HumanEval-plus) with a standout result of 96.2537; accuracy on the HumanEval benchmark achieving new state-of-the-art results across various LLM models. The code will be released at https://github.com/NinjaTech-AI/MPLE"
