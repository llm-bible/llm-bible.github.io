---
layout: publication
title: 'Nolima: Long-context Evaluation Beyond Literal Matching'
authors: Ali Modarressi, Hanieh Deilamsalehy, Franck Dernoncourt, Trung Bui, Ryan A. Rossi, Seunghyun Yoon, Hinrich Schütze
conference: "Arxiv"
year: 2025
bibkey: modarressi2025long
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.05167'}
  - {name: "Code", url: 'https://github.com/adobe-research/NoLiMa'}
tags: ['Attention Mechanism', 'Has Code', 'Transformer', 'GPT', 'Model Architecture', 'Reinforcement Learning']
---
Recent large language models (LLMs) support long contexts ranging from 128K
to 1M tokens. A popular method for evaluating these capabilities is the
needle-in-a-haystack (NIAH) test, which involves retrieving a "needle"
(relevant information) from a "haystack" (long irrelevant context). Extensions
of this approach include increasing distractors, fact chaining, and in-context
reasoning. However, in these benchmarks, models can exploit existing literal
matches between the needle and haystack to simplify the task. To address this,
we introduce NoLiMa, a benchmark extending NIAH with a carefully designed
needle set, where questions and needles have minimal lexical overlap, requiring
models to infer latent associations to locate the needle within the haystack.
We evaluate 12 popular LLMs that claim to support contexts of at least 128K
tokens. While they perform well in short contexts (<1K), performance degrades
significantly as context length increases. At 32K, for instance, 10 models drop
below 50% of their strong short-length baselines. Even GPT-4o, one of the
top-performing exceptions, experiences a reduction from an almost-perfect
baseline of 99.3% to 69.7%. Our analysis suggests these declines stem from the
increased difficulty the attention mechanism faces in longer contexts when
literal matches are absent, making it harder to retrieve relevant information.
We publicly release the dataset and evaluation code at
https://github.com/adobe-research/NoLiMa.
