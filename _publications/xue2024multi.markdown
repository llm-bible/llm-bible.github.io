---
layout: publication
title: Multi45;programming Language Ensemble For Code Generation In Large Language Model
authors: Xue Tengfei, Li Xuefeng, Azim Tahir, Smirnov Roman, Yu Jianhui, Sadrieh Arash, Pahlavan Babak
conference: "Arxiv"
year: 2024
bibkey: xue2024multi
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.04114"}
  - {name: "Code", url: "https://github.com/NinjaTech&#45;AI/MPLE"}
tags: ['Applications', 'Ethics And Bias', 'Has Code', 'RAG', 'Reinforcement Learning', 'Tools']
---
Large language models (LLMs) have significantly improved code generation particularly in one45;pass code generation. However most existing approaches focus solely on generating code in a single programming language overlooking the potential of leveraging the multi45;language capabilities of LLMs. LLMs have varying patterns of errors across different languages suggesting that a more robust approach could be developed by leveraging these multi45;language outputs. In this study we propose Multi45;Programming Language Ensemble (MPLE) a novel ensemble45;based method that utilizes code generation across multiple programming languages to enhance overall performance. By treating each language45;specific code generation process as an individual weak expert and effectively integrating their outputs our method mitigates language45;specific errors and biases. This multi45;language ensemble strategy leverages the complementary strengths of different programming languages enabling the model to produce more accurate and robust code. Our approach can be seamlessly integrated with commonly used techniques such as the reflection algorithm and Monte Carlo tree search to improve code generation quality further. Experimental results show that our framework consistently enhances baseline performance by up to 17.9237; on existing benchmarks (HumanEval and HumanEval45;plus) with a standout result of 96.2537; accuracy on the HumanEval benchmark achieving new state45;of45;the45;art results across various LLM models. The code will be released at https://github.com/NinjaTech&#45;AI/MPLE
