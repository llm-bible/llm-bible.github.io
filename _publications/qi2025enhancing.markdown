---
layout: publication
title: 'Umb@peranssumm 2025: Enhancing Perspective-aware Summarization With Prompt Optimization And Supervised Fine-tuning'
authors: Kristin Qi, Youxiang Zhu, Xiaohui Liang
conference: "Arxiv"
year: 2025
bibkey: qi2025enhancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.11118"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Tools', 'RAG', 'Pretraining Methods', 'Fine-Tuning', 'Transformer', 'Prompting', 'Applications']
---
We present our approach to the PerAnsSumm Shared Task, which involves
perspective span identification and perspective-aware summarization in
community question-answering (CQA) threads. For span identification, we adopt
ensemble learning that integrates three transformer models through averaging to
exploit individual model strengths, achieving an 82.91% F1-score on test data.
For summarization, we design a suite of Chain-of-Thought (CoT) prompting
strategies that incorporate keyphrases and guide information to structure
summary generation into manageable steps. To further enhance summary quality,
we apply prompt optimization using the DSPy framework and supervised
fine-tuning (SFT) on Llama-3 to adapt the model to domain-specific data.
Experimental results on validation and test sets show that structured prompts
with keyphrases and guidance improve summaries aligned with references, while
the combination of prompt optimization and fine-tuning together yields
significant improvement in both relevance and factuality evaluation metrics.
