---
layout: publication
title: 'Multi-step Reasoning In Korean And The Emergent Mirage'
authors: Guijin Son, Hyunwoo Ko, Dasol Choi
conference: "Arxiv"
year: 2025
bibkey: son2025multi
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.05712"}
tags: ['RAG', 'Training Techniques', 'Reinforcement Learning']
---
We introduce HRMCR (HAE-RAE Multi-Step Commonsense Reasoning), a benchmark
designed to evaluate large language models' ability to perform multi-step
reasoning in culturally specific contexts, focusing on Korean. The questions
are automatically generated via templates and algorithms, requiring LLMs to
integrate Korean cultural knowledge into sequential reasoning steps. Consistent
with prior observations on emergent abilities, our experiments reveal that
models trained on fewer than \(2 \cdot 10^\{25\}\) training FLOPs struggle to
solve any questions, showing near-zero performance. Beyond this threshold,
performance improves sharply. State-of-the-art models (e.g., O1) still score
under 50%, underscoring the difficulty of our tasks. Notably, stepwise
analysis suggests the observed emergent behavior may stem from compounding
errors across multiple steps rather than reflecting a genuinely new capability.
We publicly release the benchmark and commit to regularly updating the dataset
to prevent contamination.
