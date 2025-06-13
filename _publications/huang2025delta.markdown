---
layout: publication
title: 'Delta -- Contrastive Decoding Mitigates Text Hallucinations In Large Language Models'
authors: Cheng Peng Huang, Hao-yuan Chen
conference: "Arxiv"
year: 2025
bibkey: huang2025delta
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.05825"}
tags: ['Training Techniques', 'Prompting', 'Applications', 'Reinforcement Learning']
---
Large language models (LLMs) demonstrate strong capabilities in natural
language processing but remain prone to hallucinations, generating factually
incorrect or fabricated content. This issue undermines their reliability,
particularly in high-stakes domains such as healthcare and legal advisory. To
address this challenge, we propose Delta, an inference-time method that reduces
hallucinations without requiring model retraining or additional data. Delta
works by randomly masking parts of the input prompt and contrasting the output
distributions for the original and masked inputs, effectively suppressing
hallucinations through inference-only computations. We evaluate Delta on
context-rich question-answering benchmarks, achieving absolute improvements of
approximately 3 and 6 percentage points on SQuAD v1.1 and v2, respectively, and
7 and 2 percentage points on TriviaQA and Natural Questions under-sampling
decoding. Delta also improves the no-answer exact match score on SQuAD v2 by
over ten percentage points, demonstrating its effectiveness in mitigating
hallucinations arising from contextual ambiguity. These results highlight Delta
as a computationally efficient and scalable approach for improving the
reliability of LLMs in real-world applications.
