---
layout: publication
title: 'Full-parameter Continual Pretraining Of Gemma2: Insights Into Fluency And Domain Knowledge'
authors: Vytenis Šliogeris, Povilas Daniušis, Artūras Nakvosas
conference: "Arxiv"
year: 2025
bibkey: šliogeris2025full
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.05946"}
  - {name: "Code", url: "https://github.com/Neurotechnology/LLM_EWC"}
tags: ['GPT', 'RAG', 'Training Techniques', 'Has Code', 'Pretraining Methods']
---
In this technical report, we empirically investigate the relationship between linguistic fluency and domain knowledge in the context of continual learning with large language models (LLMs). Specifically, we enhance the linguistic fluency of the Gemma2 LLM for the Lithuanian language by autoregressively pretraining its full parameter set on the first 10% of the Lithuanian language component of the CulturaX dataset. To prevent catastrophic forgetting of the model's existing domain knowledge, we apply Elastic Weight Consolidation (EWC), leveraging Fisher information estimated using data from the Massive Multitask Language Understanding (MMLU) benchmark. In the post-training evaluations, we assess linguistic fluency through perplexity and evaluate domain knowledge using accuracy on a suite of language understanding benchmarks, including ARC-Easy, Belebele, GSM8K, HellaSwag, MMLU, TruthfulQA, and Winogrande, in both English and Lithuanian. The empirical results demonstrate that EWC not only mitigates catastrophic forgetting by preserving the model's performance in terms of both linguistic fluency and domain knowledge but also improves or maintains these capabilities for the newly added Lithuanian language. These findings highlight the potential for more efficient adaptation of general-purpose LLMs to under-represented languages without requiring access to the original training data. The accompanying codebase is openly accessible at https://github.com/Neurotechnology/LLM_EWC.
