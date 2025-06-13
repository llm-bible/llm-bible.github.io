---
layout: publication
title: 'Adapting Large Language Models For Document-level Machine Translation'
authors: Minghao Wu, Thuy-trang Vu, Lizhen Qu, George Foster, Gholamreza Haffari
conference: "Arxiv"
year: 2024
bibkey: wu2024adapting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.06468"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'GPT', 'Pretraining Methods', 'Fine-Tuning', 'Prompting', 'Applications']
---
Large language models (LLMs) have significantly advanced various natural
language processing (NLP) tasks. Recent research indicates that
moderately-sized LLMs often outperform larger ones after task-specific
fine-tuning. This study focuses on adapting LLMs for document-level machine
translation (DocMT) for specific language pairs. We first investigate the
impact of prompt strategies on translation performance and then conduct
extensive experiments using two fine-tuning methods, three LLM backbones, and
18 translation tasks across nine language pairs. Our results show that
specialized models can sometimes surpass GPT-4 in translation performance but
still face issues like off-target translation due to error propagation in
decoding. We provide an in-depth analysis of these LLMs tailored for DocMT,
examining translation errors, discourse phenomena, strategies for training and
inference, the data efficiency of parallel documents, recent test set
evaluations, and zero-shot crosslingual transfer. Our findings highlight the
strengths and limitations of LLM-based DocMT models and provide a foundation
for future research.
