---
layout: publication
title: 'Unraveling Arithmetic In Large Language Models: The Role Of Algebraic Structures'
authors: Fu-chieh Chang, You-chen Lin, Pei-yuan Wu
conference: "ICLR 2025 Workshop on Reasoning and Planning for Large Language Models"
year: 2024
bibkey: chang2024unraveling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.16260"}
tags: ['Model Architecture', 'Reinforcement Learning', 'RAG', 'Ethics and Bias', 'Pretraining Methods', 'Transformer', 'Prompting', 'Attention Mechanism']
---
Large language models (LLMs) have demonstrated remarkable mathematical
capabilities, largely driven by chain-of-thought (CoT) prompting, which
decomposes complex reasoning into step-by-step solutions. This approach has
enabled significant advancements, as evidenced by performance on benchmarks
like GSM8K and MATH. However, the mechanisms underlying LLMs' ability to
perform arithmetic in a single step of CoT remain poorly understood. Existing
studies debate whether LLMs encode numerical values or rely on symbolic
reasoning, while others explore attention and multi-layered processing in
arithmetic tasks. In this work, we propose that LLMs learn arithmetic by
capturing algebraic structures, such as commutativity and identity properties.
Since these structures are observable through input-output relationships, they
can generalize to unseen data. We empirically demonstrate that LLMs can learn
algebraic structures using a custom dataset of arithmetic problems, as well as
providing theoretical evidence showing that, under specific configurations of
weights and biases, the transformer-based LLMs can generate embeddings that
remain invariant to both permutations of input tokens and the presence of
identity elements. Our findings indicate that leveraging algebraic structures
can enhance the LLMs' arithmetic capabilities, offering insights into improving
their arithmetic performance.
