---
layout: publication
title: 'Non-markovian Discrete Diffusion With Causal Language Models'
authors: Yangtian Zhang, Sizhuang He, Daniel Levine, Lawrence Zhao, David Zhang, Syed A Rizvi, Emanuele Zappala, Rex Ying, David Van Dijk
conference: "Arxiv"
year: 2025
bibkey: zhang2025non
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.09767'}
tags: ['Transformer', 'GPT', 'Model Architecture', 'Merging', 'Pretraining Methods']
---
Discrete diffusion models offer a flexible, controllable approach to structured sequence generation, yet they still lag behind causal language models in expressive power. A key limitation lies in their reliance on the Markovian assumption, which restricts each step to condition only on the current state, leading to potential uncorrectable error accumulation. In this paper, we introduce CaDDi, a discrete diffusion model that conditions on the entire generative trajectory, thereby lifting the Markov constraint and allowing the model to revisit and improve past states. By unifying sequential (causal) and temporal (diffusion) reasoning in a single non-Markovian transformer, CaDDi also treats standard causal language models as a special case and permits the direct reuse of pretrained LLM weights with no architectural changes. Empirically, CaDDi outperforms state-of-the-art discrete diffusion baselines on natural-language benchmarks, substantially narrowing the remaining gap to large autoregressive transformers.
