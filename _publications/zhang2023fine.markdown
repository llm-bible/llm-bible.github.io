---
layout: publication
title: 'XATU: A Fine-grained Instruction-based Benchmark For Explainable Text Updates'
authors: Haopeng Zhang, Hayate Iso, Sairam Gurajada, Nikita Bhutani
conference: "Arxiv"
year: 2023
bibkey: zhang2023fine
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2309.11063'}
  - {name: "Code", url: 'https://github.com/megagonlabs/xatu'}
tags: ['Has Code', 'Interpretability and Explainability', 'Training Techniques', 'Model Architecture', 'Fine-Tuning', 'Reinforcement Learning', 'Interpretability', 'Pretraining Methods']
---
Text editing is a crucial task of modifying text to better align with user
intents. However, existing text editing benchmark datasets contain only
coarse-grained instructions and lack explainability, thus resulting in outputs
that deviate from the intended changes outlined in the gold reference. To
comprehensively investigate the text editing capabilities of large language
models (LLMs), this paper introduces XATU, the first benchmark specifically
designed for fine-grained instruction-based explainable text editing. XATU
considers finer-grained text editing tasks of varying difficulty
(simplification, grammar check, fact-check, etc.), incorporating lexical,
syntactic, semantic, and knowledge-intensive edit aspects. To enhance
interpretability, we combine LLM-based annotation and human annotation,
resulting in a benchmark that includes fine-grained instructions and
gold-standard edit explanations. By evaluating existing LLMs against our
benchmark, we demonstrate the effectiveness of instruction tuning and the
impact of underlying architecture across various editing tasks. Furthermore,
extensive experimentation reveals the significant role of explanations in
fine-tuning language models for text editing tasks. The benchmark will be
open-sourced to support reproduction and facilitate future research
at~\url\{https://github.com/megagonlabs/xatu\}.
