---
layout: publication
title: 'It''s All In The [MASK]: Simple Instruction-tuning Enables Bert-like Masked Language Models As Generative Classifiers'
authors: Benjamin Clavié, Nathan Cooper, Benjamin Warner
conference: "Arxiv"
year: 2025
bibkey: clavié2025all
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.03793"}
tags: ['Fine-Tuning', 'Applications', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Masked Language Model', 'Training Techniques', 'Pretraining Methods', 'BERT', 'Prompting']
---
While encoder-only models such as BERT and ModernBERT are ubiquitous in
real-world NLP applications, their conventional reliance on task-specific
classification heads can limit their applicability compared to decoder-based
large language models (LLMs). In this work, we introduce
ModernBERT-Large-Instruct, a 0.4B-parameter encoder model that leverages its
masked language modelling (MLM) head for generative classification. Our
approach employs an intentionally simple training loop and inference mechanism
that requires no heavy pre-processing, heavily engineered prompting, or
architectural modifications. ModernBERT-Large-Instruct exhibits strong
zero-shot performance on both classification and knowledge-based tasks,
outperforming similarly sized LLMs on MMLU and achieving 93% of Llama3-1B's
MMLU performance with 60% less parameters. We also demonstrate that, when
fine-tuned, the generative approach using the MLM head matches or even
surpasses traditional classification-head methods across diverse NLU tasks.This
capability emerges specifically in models trained on contemporary, diverse data
mixes, with models trained on lower volume, less-diverse data yielding
considerably weaker performance. Although preliminary, these results
demonstrate the potential of using the original generative masked language
modelling head over traditional task-specific heads for downstream tasks. Our
work suggests that further exploration into this area is warranted,
highlighting many avenues for future improvements.
