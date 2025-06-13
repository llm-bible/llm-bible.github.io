---
layout: publication
title: 'HAPO: Training Language Models To Reason Concisely Via History-aware Policy Optimization'
authors: Chengyu Huang, Zhengxin Zhang, Claire Cardie
conference: "Arxiv"
year: 2025
bibkey: huang2025training
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.11225"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Reinforcement Learning', 'RAG', 'Fine-Tuning']
---
While scaling the length of responses at test-time has been shown to markedly improve the reasoning abilities and performance of large language models (LLMs), it often results in verbose outputs and increases inference cost. Prior approaches for efficient test-time scaling, typically using universal budget constraints or query-level length optimization, do not leverage historical information from previous encounters with the same problem during training. We hypothesize that this limits their ability to progressively make solutions more concise over time. To address this, we present History-Aware Policy Optimization (HAPO), which keeps track of a history state (e.g., the minimum length over previously generated correct responses) for each problem. HAPO employs a novel length reward function based on this history state to incentivize the discovery of correct solutions that are more concise than those previously found. Crucially, this reward structure avoids overly penalizing shorter incorrect responses with the goal of facilitating exploration towards more efficient solutions. By combining this length reward with a correctness reward, HAPO jointly optimizes for correctness and efficiency. We use HAPO to train DeepSeek-R1-Distill-Qwen-1.5B, DeepScaleR-1.5B-Preview, and Qwen-2.5-1.5B-Instruct, and evaluate HAPO on several math benchmarks that span various difficulty levels. Experiment results demonstrate that HAPO effectively induces LLMs' concise reasoning abilities, producing length reductions of 33-59% with accuracy drops of only 2-5%.
