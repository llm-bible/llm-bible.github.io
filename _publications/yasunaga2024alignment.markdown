---
layout: publication
title: 'ALMA: Alignment With Minimal Annotation'
authors: Michihiro Yasunaga, Leonid Shamis, Chunting Zhou, Andrew Cohen, Jason Weston, Luke Zettlemoyer, Marjan Ghazvininejad
conference: "Arxiv"
year: 2024
bibkey: yasunaga2024alignment
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.04305'}
tags: ['Few-Shot', 'Efficiency and Optimization', 'Distillation', 'Training Techniques', 'Fine-Tuning', 'Prompting', 'Reinforcement Learning']
---
Recent approaches to large language model (LLM) alignment typically require
millions of human annotations or rely on external aligned models for synthetic
data generation. This paper introduces ALMA: Alignment with Minimal Annotation,
demonstrating that effective alignment can be achieved using only 9,000 labeled
examples -- less than 1% of conventional approaches. ALMA generates large
amounts of high-quality synthetic alignment data through new techniques:
diverse prompt synthesis via few-shot learning, diverse response generation
with multiple model checkpoints, and judge (reward model) enhancement through
score aggregation and self-distillation. Using only a pretrained Llama3 base
model, 5,000 SFT examples, and 4,000 judge annotations, ALMA achieves
performance close to Llama3-Instruct across diverse alignment benchmarks (e.g.,
0.1% difference on AlpacaEval 2.0 score). These results are achieved with a
multi-round, self-bootstrapped data synthesis and training recipe that
continues to improve for 10 rounds, surpassing the typical 3-round ceiling of
previous methods. These results suggest that base models already possess
sufficient knowledge for effective alignment, and that synthetic data
generation methods can expose it.
