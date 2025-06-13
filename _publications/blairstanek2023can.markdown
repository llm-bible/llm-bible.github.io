---
layout: publication
title: 'BLT: Can Large Language Models Handle Basic Legal Text?'
authors: Andrew Blair-stanek, Nils Holzenberger, Benjamin Van Durme
conference: "Arxiv"
year: 2023
bibkey: blairstanek2023can
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.09693"}
tags: ['Fine-Tuning', 'GPT', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods']
---
We find that the best publicly available LLMs like GPT-4 and Claude currently
perform poorly on basic legal text handling. This motivates the creation of a
benchmark consisting of examples that lawyers and paralegals would expect LLMs
to handle zero-shot, such as looking up the text at a line of a witness
deposition or at a subsection of a contract. LLMs' poor performance on this
benchmark casts into doubt their reliability as-is for legal practice. However,
fine-tuning on our training set brings even a small model to near-perfect
performance. This benchmark will be useful for fine-tuning LLMs for downstream
legal tasks, as well as for tracking LLMs' reliability as-is for basic legal
tasks.
