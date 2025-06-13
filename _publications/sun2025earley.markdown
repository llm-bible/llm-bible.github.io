---
layout: publication
title: 'Earley-driven Dynamic Pruning For Efficient Structured Decoding'
authors: Xintong Sun, Chi Wei, Minghao Tian, Shiwen Ni
conference: "Arxiv"
year: 2025
bibkey: sun2025earley
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.01151"}
  - {name: "Code", url: "https://github.com/Dan-wanna-M/formatron"}
tags: ['Efficiency and Optimization', 'Model Architecture', 'Pruning', 'Reinforcement Learning', 'Has Code']
---
Large Language Models (LLMs) have shown remarkable capabilities, yet ensuring their outputs conform to strict structural or grammatical constraints remains challenging, which is critical in function calls and domain-specific language (DSL) generation. Constrained decoding with context-free grammar is a flexible approach to guarantee LLMs' adherence to a specific format by dynamically building a token logits mask. However, creating this mask requires checking the validity of all tokens in the LLM vocabulary at every decoding step, which often incurs significant overheads in existing constrained decoding engines. To address this challenge, we propose \\(\textbf\{ZapFormat\}\\), a novel \\(\textbf\{dynamic pruning\}\\) strategy based on the Earley algorithm that identifies and eliminates invalid or redundant Earley states in real-time, significantly reducing memory occupation of the Earley algorithm's states. This further enables us to use a state cache to speed up structured generations on a large number of queries. We implemented ZapFormat in a new constrained decoding engine called Formatron which also incorporates existing optimizations. Through comprehensive experiments on structured generation tasks, including JSON generation, JSON Schema validation, and semantic parsing, we demonstrate that Formatron not only \\(\textbf\{consistently maintains\}\\) high-precision compliant outputs but also achieves \\(\textbf\{significant improvements\}\\) in inference speed up to 2x compared to state-of-the-art implementations. More importantly, Formatron is generally applicable across various LLM architectures. We release Formatron as open source at https://github.com/Dan-wanna-M/formatron.
