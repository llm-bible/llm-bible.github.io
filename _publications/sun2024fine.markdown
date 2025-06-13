---
layout: publication
title: 'Fine-grained And Multi-dimensional Metrics For Document-level Machine Translation'
authors: Yirong Sun, Dawei Zhu, Yanjun Chen, Erjia Xiao, Xinghao Chen, Xiaoyu Shen
conference: "Arxiv"
year: 2024
bibkey: sun2024fine
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.20941'}
  - {name: "Code", url: 'https://github.com/EIT-NLP/BLEUless_DocMT'}
tags: ['Has Code', 'RAG', 'Training Techniques', 'GPT', 'Model Architecture', 'Fine-Tuning', 'Prompting', 'Applications', 'Pretraining Methods']
---
Large language models (LLMs) have excelled in various NLP tasks, including
machine translation (MT), yet most studies focus on sentence-level translation.
This work investigates the inherent capability of instruction-tuned LLMs for
document-level translation (docMT). Unlike prior approaches that require
specialized techniques, we evaluate LLMs by directly prompting them to
translate entire documents in a single pass. Our results show that this method
improves translation quality compared to translating sentences separately, even
without document-level fine-tuning. However, this advantage is not reflected in
BLEU scores, which often favor sentence-based translations. We propose using
the LLM-as-a-judge paradigm for evaluation, where GPT-4 is used to assess
document coherence, accuracy, and fluency in a more nuanced way than
n-gram-based metrics. Overall, our work demonstrates that instruction-tuned
LLMs can effectively leverage document context for translation. However, we
caution against using BLEU scores for evaluating docMT, as they often provide
misleading outcomes, failing to capture the quality of document-level
translation. Code and the outputs from GPT4-as-a-judge are available at
https://github.com/EIT-NLP/BLEUless_DocMT
