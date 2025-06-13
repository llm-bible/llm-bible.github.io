---
layout: publication
title: 'When Llms Struggle: Reference-less Translation Evaluation For Low-resource Languages'
authors: Archchana Sindhujan, Diptesh Kanojia, Constantin Orasan, Shenbin Qian
conference: "Arxiv"
year: 2025
bibkey: sindhujan2025when
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2501.04473'}
tags: ['Few-Shot', 'Training Techniques', 'Applications', 'Fine-Tuning', 'Prompting', 'Pre-Training', 'Tokenization', 'Pretraining Methods']
---
This paper investigates the reference-less evaluation of machine translation
for low-resource language pairs, known as quality estimation (QE).
Segment-level QE is a challenging cross-lingual language understanding task
that provides a quality score (0-100) to the translated output. We
comprehensively evaluate large language models (LLMs) in zero/few-shot
scenarios and perform instruction fine-tuning using a novel prompt based on
annotation guidelines. Our results indicate that prompt-based approaches are
outperformed by the encoder-based fine-tuned QE models. Our error analysis
reveals tokenization issues, along with errors due to transliteration and named
entities, and argues for refinement in LLM pre-training for cross-lingual
tasks. We release the data, and models trained publicly for further research.
