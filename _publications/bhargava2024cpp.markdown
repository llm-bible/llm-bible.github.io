---
layout: publication
title: 'Cpp-ut-bench: Can Llms Write Complex Unit Tests In C++?'
authors: Vaishnavi Bhargava, Rajat Ghosh, Debojyoti Dutta
conference: "Arxiv"
year: 2024
bibkey: bhargava2024cpp
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.02735'}
tags: ['RAG', 'Training Techniques', 'Fine-Tuning', 'Prompting', 'Reinforcement Learning', 'In-Context Learning', 'Pretraining Methods']
---
We introduce CPP-UT-Bench, a benchmark dataset to measure C++ unit test
generation capability of a large language model (LLM). CPP-UT-Bench aims to
reflect a broad and diverse set of C++ codebases found in the real world. The
dataset includes 2,653 \{code, unit test\} pairs drawn from 14 different
opensource C++ codebases spanned across nine diverse domains including machine
learning, software testing, parsing, standard input-output, data engineering,
logging, complete expression evaluation, key value storage, and server
protocols. We demonstrated the effectiveness of CPP-UT-Bench as a benchmark
dataset through extensive experiments in in-context learning,
parameter-efficient fine-tuning (PEFT), and full-parameter fine-tuning. We also
discussed the challenges of the dataset compilation and insights we learned
from in-context learning and fine-tuning experiments. Besides the CPP-UT-Bench
dataset and data compilation code, we are also offering the fine-tuned model
weights for further research. For nine out of ten experiments, our fine-tuned
LLMs outperformed the corresponding base models by an average of more than 70%.
