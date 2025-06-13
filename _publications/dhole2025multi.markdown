---
layout: publication
title: 'A Multi-encoder Frozen-decoder Approach For Fine-tuning Large Language Models'
authors: Kaustubh D. Dhole
conference: "Arxiv"
year: 2025
bibkey: dhole2025multi
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.07818"}
tags: ['Fine-Tuning', 'Training Techniques', 'Pretraining Methods']
---
Among parameter-efficient fine-tuning methods, freezing has emerged as a
popular strategy for speeding up training, reducing catastrophic forgetting,
and improving downstream performance. We investigate the impact of freezing the
decoder in a multi-task setup comprising diverse natural language tasks, aiming
to reduce deployment overhead and enhance portability to novel tasks. Our
experiments, conducted by fine-tuning both individual and multi-task setups on
the AlexaTM model, reveal that freezing decoders is highly effective for tasks
with natural language outputs and mitigates catastrophic forgetting in
multilingual tasks. However, we find that pairing frozen decoders with a larger
model can effectively maintain or even enhance performance in structured and QA
tasks, making it a viable strategy for a broader range of task types.
