---
layout: publication
title: '\(\texttt{sem-ctrl}\): Semantically Controlled Decoding'
authors: Mohammad Albinhassan, Pranava Madhyastha, Alessandra Russo
conference: "Arxiv"
year: 2025
bibkey: albinhassan2025semantically
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.01804'}
tags: ['Reinforcement Learning', 'Fine-Tuning', 'Training Techniques', 'Pretraining Methods']
---
Ensuring both syntactic and semantic correctness in Large Language Model
(LLM) outputs remains a significant challenge, despite being critical for
real-world deployment. In this paper, we introduce \\(\texttt\{SEM-CTRL\}\\), a
unified approach that enforces rich context-sensitive constraints and task- and
instance-specific semantics directly on an LLM decoder. Our approach integrates
token-level MCTS, which is guided by specific syntactic and semantic
constraints. The constraints over the desired outputs are expressed using
Answer Set Grammars -- a logic-based formalism that generalizes
context-sensitive grammars while incorporating background knowledge to
represent task-specific semantics. We show that our approach guarantees correct
completions for any off-the-shelf LLM without the need for fine-tuning. We
evaluate \\(\texttt\{SEM-CTRL\}\\) on a range of tasks, including synthetic grammar
synthesis, combinatorial reasoning, and planning. Our results demonstrate that
\\(\texttt\{SEM-CTRL\}\\) allows small pre-trained LLMs to efficiently outperform
larger variants and state-of-the-art reasoning models (e.g., o1-preview) while
simultaneously guaranteeing solution correctness.
