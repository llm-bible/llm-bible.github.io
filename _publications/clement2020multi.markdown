---
layout: publication
title: 'Pymt5: Multi-mode Translation Of Natural Language And Python Code With Transformers'
authors: Clement Colin B., Drain Dawn, Timcheck Jonathan, Svyatkovskiy Alexey, Sundaresan Neel
conference: "Arxiv"
year: 2020
bibkey: clement2020multi
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2010.03150"}
tags: ['Applications', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Transformer']
---
Simultaneously modeling source code and natural language has many exciting
applications in automated software development and understanding. Pursuant to
achieving such technology, we introduce PyMT5, the Python method text-to-text
transfer transformer, which is trained to translate between all pairs of Python
method feature combinations: a single model that can both predict whole methods
from natural language documentation strings (docstrings) and summarize code
into docstrings of any common style. We present an analysis and modeling effort
of a large-scale parallel corpus of 26 million Python methods and 7.7 million
method-docstring pairs, demonstrating that for docstring and method generation,
PyMT5 outperforms similarly-sized auto-regressive language models (GPT2) which
were English pre-trained or randomly initialized. On the CodeSearchNet test
set, our best model predicts 92.1% syntactically correct method bodies,
achieved a BLEU score of 8.59 for method generation and 16.3 for docstring
generation (summarization), and achieved a ROUGE-L F-score of 24.8 for method
generation and 36.7 for docstring generation.
