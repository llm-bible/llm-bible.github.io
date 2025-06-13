---
layout: publication
title: 'Promptdistill: Query-based Selective Token Retention In Intermediate Layers For Efficient Large Language Model Inference'
authors: Weisheng Jin, Maojia Song, Tej Deep Pala, Yew Ken Chia, Amir Zadeh, Chuan Li, Soujanya Poria
conference: "Arxiv"
year: 2025
bibkey: jin2025query
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.23274"}
tags: ['Efficiency and Optimization', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Attention Mechanism', 'Prompting']
---
As large language models (LLMs) tackle increasingly complex tasks and longer
documents, their computational and memory costs during inference become a major
bottleneck. To address this, we propose PromptDistill, a novel, training-free
method that improves inference efficiency while preserving generation quality.
PromptDistill identifies and retains the most informative tokens by leveraging
attention interactions in early layers, preserving their hidden states while
reducing the computational burden in later layers. This allows the model to
focus on essential contextual information without fully processing all tokens.
Unlike previous methods such as H2O and SnapKV, which perform compression only
after processing the entire input, or GemFilter, which selects a fixed portion
of the initial prompt without considering contextual dependencies,
PromptDistill dynamically allocates computational resources to the most
relevant tokens while maintaining a global awareness of the input. Experiments
using our method and baseline approaches with base models such as LLaMA 3.1 8B
Instruct, Phi 3.5 Mini Instruct, and Qwen2 7B Instruct on benchmarks including
LongBench, InfBench, and Needle in a Haystack demonstrate that PromptDistill
significantly improves efficiency while having minimal impact on output quality
compared to the original models. With a single-stage selection strategy,
PromptDistill effectively balances performance and efficiency, outperforming
prior methods like GemFilter, H2O, and SnapKV due to its superior ability to
retain essential information. Specifically, compared to GemFilter,
PromptDistill achieves an overall \\(1%\\) to \\(5%\\) performance improvement while
also offering better time efficiency. Additionally, we explore multi-stage
selection, which further improves efficiency while maintaining strong
generation performance.
