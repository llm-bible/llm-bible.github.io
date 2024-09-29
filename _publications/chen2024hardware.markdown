---
layout: publication
title: Hardware45;aware Parallel Prompt Decoding For Memory45;efficient Acceleration Of LLM Inference
authors: Chen Hao Mark, Luk Wayne, Yiu Ka Fai Cedric, Li Rui, Mishchenko Konstantin, Venieris Stylianos I., Fan Hongxiang
conference: "Arxiv"
year: 2024
bibkey: chen2024hardware
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.18628"}
  - {name: "Code", url: "https://github.com/hmarkc/parallel&#45;prompt&#45;decoding"}
tags: ['Applications', 'Efficiency And Optimization', 'Has Code', 'Prompting', 'RAG', 'Training Techniques']
---
The auto45;regressive decoding of Large Language Models (LLMs) results in significant overheads in their hardware performance. While recent research has investigated various speculative decoding techniques for multi45;token generation these efforts have primarily focused on improving processing speed such as throughput. Crucially they often neglect other metrics essential for real45;life deployments such as memory consumption and training cost. To overcome these limitations we propose a novel parallel prompt decoding that requires only 0.000237; trainable parameters enabling efficient training on a single A10045;40GB GPU in just 16 hours. Inspired by the human natural language generation process PPD approximates outputs generated at future timesteps in parallel by using multiple prompt tokens. This approach partially recovers the missing conditional dependency information necessary for multi45;token generation resulting in up to a 2837; higher acceptance rate for long45;range predictions. Furthermore we present a hardware45;aware dynamic sparse tree technique that adaptively optimizes this decoding scheme to fully leverage the computational capacities on different GPUs. Through extensive experiments across LLMs ranging from MobileLlama to Vicuna45;13B on a wide range of benchmarks our approach demonstrates up to 2.49× speedup and maintains a minimal runtime memory overhead of just 0.000437;. More importantly our parallel prompt decoding can serve as an orthogonal optimization for synergistic integration with existing speculative decoding showing up to 1.22× further speed improvement. Our code is available at https://github.com/hmarkc/parallel&#45;prompt&#45;decoding.
