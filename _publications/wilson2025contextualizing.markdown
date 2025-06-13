---
layout: publication
title: 'Contextualizing Search Queries In-context Learning For Conversational Rewriting With Llms'
authors: Raymond Wilson, Chase Carter, Cole Graham
conference: "Arxiv"
year: 2025
bibkey: wilson2025contextualizing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.15009"}
tags: ['Training Techniques', 'Few-Shot', 'RAG', 'Pretraining Methods', 'Fine-Tuning', 'Prompting', 'In-Context Learning']
---
Conversational query rewriting is crucial for effective conversational
search, yet traditional supervised methods require substantial labeled data,
which is scarce in low-resource settings. This paper introduces Prompt-Guided
In-Context Learning, a novel approach that leverages the in-context learning
capabilities of Large Language Models (LLMs) for few-shot conversational query
rewriting. Our method employs carefully designed prompts, incorporating task
descriptions, input/output format specifications, and a small set of
illustrative examples, to guide pre-trained LLMs to generate
context-independent queries without explicit fine-tuning. Extensive experiments
on benchmark datasets, TREC and Taskmaster-1, demonstrate that our approach
significantly outperforms strong baselines, including supervised models and
contrastive co-training methods, across various evaluation metrics such as
BLEU, ROUGE-L, Success Rate, and MRR. Ablation studies confirm the importance
of in-context examples, and human evaluations further validate the superior
fluency, relevance, and context utilization of our generated rewrites. The
results highlight the potential of prompt-guided in-context learning as an
efficient and effective paradigm for low-resource conversational query
rewriting, reducing the reliance on extensive labeled data and complex training
procedures.
