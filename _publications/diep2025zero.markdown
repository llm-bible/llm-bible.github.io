---
layout: publication
title: 'On Zero-initialized Attention: Optimal Prompt And Gating Factor Estimation'
authors: Nghiem T. Diep, Huy Nguyen, Chau Nguyen, Minh Le, Duy M. H. Nguyen, Daniel Sonntag, Mathias Niepert, Nhat Ho
conference: "Arxiv"
year: 2025
bibkey: diep2025zero
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.03029"}
tags: ['Fine-Tuning', 'Applications', 'RAG', 'Model Architecture', 'Security', 'Training Techniques', 'Attention Mechanism', 'Pretraining Methods', 'Prompting']
---
The LLaMA-Adapter has recently emerged as an efficient fine-tuning technique
for LLaMA models, leveraging zero-initialized attention to stabilize training
and enhance performance. However, despite its empirical success, the
theoretical foundations of zero-initialized attention remain largely
unexplored. In this paper, we provide a rigorous theoretical analysis,
establishing a connection between zero-initialized attention and
mixture-of-expert models. We prove that both linear and non-linear prompts,
along with gating functions, can be optimally estimated, with non-linear
prompts offering greater flexibility for future applications. Empirically, we
validate our findings on the open LLM benchmarks, demonstrating that non-linear
prompts outperform linear ones. Notably, even with limited training data, both
prompt types consistently surpass vanilla attention, highlighting the
robustness and adaptability of zero-initialized attention.
