---
layout: publication
title: 'Development And Bilingual Evaluation Of Japanese Medical Large Language Model Within Reasonably Low Computational Resources'
authors: Issey Sukeda
conference: "Arxiv"
year: 2024
bibkey: sukeda2024development
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.11783"}
  - {name: "Code", url: "https://github.com/stardust-coder/japanese-lm-med-harness"}
tags: ['Fine-Tuning', 'Reinforcement Learning', 'Security', 'Training Techniques', 'Has Code', 'Pretraining Methods']
---
The recent success of large language models (LLMs) and the scaling law has
led to a widespread adoption of larger models. Particularly in the healthcare
industry, there is an increasing demand for locally operated LLMs due to
security concerns. However, the majority of high quality open-source LLMs have
a size of 70B parameters, imposing significant financial burdens on users for
GPU preparation and operation. To overcome these issues, we present a medical
adaptation based on the recent 7B models, which enables the operation in low
computational resources. We compare the performance on medical
question-answering benchmarks in two languages (Japanese and English),
demonstrating that its scores reach parity with or surpass those of currently
existing medical LLMs that are ten times larger. We find that fine-tuning an
English-centric base model on Japanese medical dataset improves the score in
both language, supporting the effect of cross-lingual knowledge transfer. We
hope that this study will alleviate financial challenges, serving as a stepping
stone for clinical institutions to practically utilize LLMs locally. Our
evaluation code is available at
https://github.com/stardust-coder/japanese-lm-med-harness.
