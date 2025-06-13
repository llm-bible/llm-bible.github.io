---
layout: publication
title: 'Top-training: Target-oriented Pretraining For Medical Extractive Question Answering'
authors: Saptarshi Sengupta, Connor Heaton, Shreya Ghosh, Wenpeng Yin, Preslav Nakov, Suhang Wang
conference: "Arxiv"
year: 2023
bibkey: sengupta2023top
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.16995"}
tags: ['Training Techniques', 'RAG', 'GPT', 'Pretraining Methods', 'Fine-Tuning', 'Pre-Training', 'Applications']
---
We study extractive question-answering in the medical domain (Medical-EQA).
This problem has two main challenges: (i) domain specificity, as most AI models
lack necessary domain knowledge, and (ii) extraction-based answering style,
which restricts most autoregressive LLMs due to potential hallucinations. To
handle those challenges, we propose TOP-Training, a target-oriented
pre-training paradigm that stands out among all domain adaptation techniques
with two desirable features: (i) TOP-Training moves one step further than
popular domain-oriented fine-tuning since it not only moves closer to the
target domain, but also familiarizes itself with the target dataset, and (ii)
it does not assume the existence of a large set of unlabeled instances from the
target domain. Specifically, for a target Medical-EQA dataset, we extract its
entities and leverage large language models (LLMs) to generate synthetic texts
containing those entities; we then demonstrate that pretraining on this
synthetic text data yields better performance on the target Medical-EQA
benchmarks. Overall, our contributions are threefold: (i) TOP-Training, a new
pretraining technique to effectively adapt LLMs to better solve a target
problem, (ii) TOP-Training has a wide application scope because it does not
require the target problem to have a large set of unlabeled data, and (iii) our
experiments highlight the limitations of autoregressive LLMs, emphasizing
TOP-Training as a means to unlock the true potential of bidirectional LLMs.
