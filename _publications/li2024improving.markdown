---
layout: publication
title: 'Think&cite: Improving Attributed Text Generation With Self-guided Tree Search And Progress Reward Modeling'
authors: Junyi Li, Hwee Tou Ng
conference: "Arxiv"
year: 2024
bibkey: li2024improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.14860"}
tags: ['Tools', 'Applications', 'Language Modeling', 'Reinforcement Learning', 'Prompting']
---
Despite their outstanding capabilities, large language models (LLMs) are
prone to hallucination and producing factually incorrect information. This
challenge has spurred efforts in attributed text generation, which prompts LLMs
to generate content with supporting evidence. In this paper, we propose a novel
framework, called Think&Cite, and formulate attributed text generation as a
multi-step reasoning problem integrated with search. Specifically, we propose
Self-Guided Monte Carlo Tree Search (SG-MCTS), which capitalizes on the
self-reflection capability of LLMs to reflect on the intermediate states of
MCTS for guiding the tree expansion process. To provide reliable and
comprehensive feedback, we introduce Progress Reward Models to measure the
progress of tree search from the root to the current state from two aspects,
i.e., generation and attribution progress. We conduct extensive experiments on
three datasets and the results show that our approach significantly outperforms
baseline approaches.
