---
layout: publication
title: 'Self-translate-train: Enhancing Cross-lingual Transfer Of Large Language Models Via Inherent Capability'
authors: Ryokan Ri, Shun Kiyono, Sho Takase
conference: "Arxiv"
year: 2024
bibkey: ri2024self
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2407.00454'}
tags: ['RAG', 'Fine-Tuning', 'Training Techniques', 'Pretraining Methods']
---
Zero-shot cross-lingual transfer by fine-tuning multilingual pretrained
models shows promise for low-resource languages, but often suffers from
misalignment of internal representations between languages. We hypothesize that
even when the model cannot generalize across languages effectively in
fine-tuning, it still captures cross-lingual correspondence useful for
cross-lingual transfer. We explore this hypothesis with Self-Translate-Train, a
method that lets large language models (LLMs) to translate training data into
the target language and fine-tunes the model on its own generated data. By
demonstrating that Self-Translate-Train outperforms zero-shot transfer, we
encourage further exploration of better methods to elicit cross-lingual
capabilities of LLMs.
