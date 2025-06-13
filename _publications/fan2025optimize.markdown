---
layout: publication
title: 'GRAPE: Optimize Data Mixture For Group Robust Multi-target Adaptive Pretraining'
authors: Simin Fan, Maria Ios Glarou, Martin Jaggi
conference: "Arxiv"
year: 2025
bibkey: fan2025optimize
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.20380'}
tags: ['Language Modeling', 'RAG', 'Efficiency and Optimization', 'Applications', 'Tools', 'Training Techniques', 'Reinforcement Learning', 'Pretraining Methods']
---
The performance of large language models (LLMs) across diverse downstream applications is fundamentally governed by the quality and composition of their pretraining corpora. Existing domain reweighting algorithms primarily optimize data mixtures for a single target task, thereby resulting in models that overfit to specialized objectives while exhibiting substantial performance degradation on other benchmarks. This paper introduces Group Robust Multi-target Adaptive PrEtraining (GRAPE), a novel multi-source-multi-target domain reweighting framework designed to calibrate pretraining data mixtures for robust performance across multiple target tasks simultaneously. GRAPE dynamically adjusts sampling weights across source domains (domain weights) while concurrently modulating task weights that quantify the relative importance of each individual target task. This adaptive process prioritizes tasks based on their learning difficulty throughout training. We formulate this interleaved reweighting mechanism as a minimax optimization problem: The inner maximization adjusts task weights leveraging group distributed-robust-optimization (DRO), where those tasks demonstrating the least improvement under the current data mixture are prioritized with higher weights; The outer minimization then optimizes domain weights to maximize loss reduction on the prioritized tasks. Experiments on ClimbLab and SlimPajama datasets demonstrate that GRAPE consistently outperforms baseline methods in terms of reasoning performance across 6 benchmarks. Furthermore, when applied to multilingual targets, GRAPE effectively identifies optimal training mixtures from mainstream languages, achieving superior language modeling capabilities across 8 low-resource target languages.
