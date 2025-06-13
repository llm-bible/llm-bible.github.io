---
layout: publication
title: 'Stacking Small Language Models For Generalizability'
authors: Laurence Liang
conference: "Arxiv"
year: 2024
bibkey: liang2024stacking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.15570"}
tags: ['Training Techniques', 'Reinforcement Learning', 'Pretraining Methods', 'Fine-Tuning', 'Interpretability and Explainability']
---
Recent advances show that large language models (LLMs) generalize strong
performance across different natural language benchmarks. However, the large
size of LLMs makes training and inference expensive and impractical to run in
resource-limited settings. This paper introduces a new approach called
fine-tuning stacks of language models (FSLM), which involves stacking small
language models (SLM) as an alternative to LLMs. By fine-tuning each SLM to
perform a specific task, this approach breaks down high level reasoning into
multiple lower-level steps that specific SLMs are responsible for. As a result,
FSLM allows for lower training and inference costs, and also improves model
interpretability as each SLM communicates with the subsequent one through
natural language. By evaluating FSLM on common natural language benchmarks,
this paper highlights promising early results toward generalizable performance
using FSLM as a cost-effective alternative to LLMs.
