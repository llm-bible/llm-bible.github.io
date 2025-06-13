---
layout: publication
title: 'Beyond Fine-tuning: Unleashing The Potential Of Continuous Pretraining For Clinical Llms'
authors: Clément Christophe, Tathagata Raha, Svetlana Maslenkova, Muhammad Umar Salman, Praveen K Kanithi, Marco Af Pimentel, Shadab Khan
conference: "Arxiv"
year: 2024
bibkey: christophe2024beyond
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2409.14988'}
tags: ['RAG', 'Training Techniques', 'Applications', 'Fine-Tuning', 'Prompting', 'Pretraining Methods']
---
Large Language Models (LLMs) have demonstrated significant potential in
transforming clinical applications. In this study, we investigate the efficacy
of four techniques in adapting LLMs for clinical use-cases: continuous
pretraining, instruct fine-tuning, NEFTune, and prompt engineering. We employ
these methods on Mistral 7B and Mixtral 8x7B models, leveraging a large-scale
clinical pretraining dataset of 50 billion tokens and an instruct fine-tuning
dataset of 500 million tokens. Our evaluation across various clinical tasks
reveals the impact of each technique. While continuous pretraining beyond 250
billion tokens yields marginal improvements on its own, it establishes a strong
foundation for instruct fine-tuning. Notably, NEFTune, designed primarily to
enhance generation quality, surprisingly demonstrates additional gains on our
benchmark. Complex prompt engineering methods further enhance performance.
These findings show the importance of tailoring fine-tuning strategies and
exploring innovative techniques to optimize LLM performance in the clinical
domain.
