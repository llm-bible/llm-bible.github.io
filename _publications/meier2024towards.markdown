---
layout: publication
title: 'Towards Human Understanding Of Paraphrase Types In Large Language Models'
authors: Dominik Meier, Jan Philip Wahle, Terry Ruas, Bela Gipp
conference: "Proceedings of the 31st International Conference on Computational Linguistics (2025) pages 6298-6316"
year: 2024
bibkey: meier2024towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.02302"}
tags: ['GPT', 'Interpretability and Explainability', 'Model Architecture', 'Reinforcement Learning', 'Prompting']
---
Paraphrases represent a human's intuitive ability to understand expressions
presented in various different ways. Current paraphrase evaluations of language
models primarily use binary approaches, offering limited interpretability of
specific text changes. Atomic paraphrase types (APT) decompose paraphrases into
different linguistic changes and offer a granular view of the flexibility in
linguistic expression (e.g., a shift in syntax or vocabulary used). In this
study, we assess the human preferences towards ChatGPT in generating English
paraphrases with ten APTs and five prompting techniques. We introduce APTY
(Atomic Paraphrase TYpes), a dataset of 800 sentence-level and word-level
annotations by 15 annotators. The dataset also provides a human preference
ranking of paraphrases with different types that can be used to fine-tune
models with RLHF and DPO methods. Our results reveal that ChatGPT and a
DPO-trained LLama 7B model can generate simple APTs, such as additions and
deletions, but struggle with complex structures (e.g., subordination changes).
This study contributes to understanding which aspects of paraphrasing language
models have already succeeded at understanding and what remains elusive. In
addition, we show how our curated datasets can be used to develop language
models with specific linguistic capabilities.
