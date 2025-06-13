---
layout: publication
title: 'Vericoder: Enhancing Llm-based RTL Code Generation Through Functional Correctness Validation'
authors: Anjiang Wei, Huanmi Tan, Tarun Suresh, Daniel Mendoza, Thiago S. F. X. Teixeira, Ke Wang, Caroline Trippel, Alex Aiken
conference: "Arxiv"
year: 2025
bibkey: wei2025enhancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.15659"}
tags: ['Training Techniques', 'Model Architecture', 'Reinforcement Learning', 'GPT', 'Pretraining Methods', 'Fine-Tuning', 'Prompting', 'Applications']
---
Recent advances in Large Language Models (LLMs) have sparked growing interest
in applying them to Electronic Design Automation (EDA) tasks, particularly
Register Transfer Level (RTL) code generation. While several RTL datasets have
been introduced, most focus on syntactic validity rather than functional
validation with tests, leading to training examples that compile but may not
implement the intended behavior. We present VERICODER, a model for RTL code
generation fine-tuned on a dataset validated for functional correctness. This
fine-tuning dataset is constructed using a novel methodology that combines unit
test generation with feedback-directed refinement. Given a natural language
specification and an initial RTL design, we prompt a teacher model
(GPT-4o-mini) to generate unit tests and iteratively revise the RTL design
based on its simulation results using the generated tests. If necessary, the
teacher model also updates the tests to ensure they comply with the natural
language specification. As a result of this process, every example in our
dataset is functionally validated, consisting of a natural language
description, an RTL implementation, and passing tests. Fine-tuned on this
dataset of over 125,000 examples, VERICODER achieves state-of-the-art metrics
in functional correctness on VerilogEval and RTLLM, with relative gains of up
to 71.7% and 27.4% respectively. An ablation study further shows that models
trained on our functionally validated dataset outperform those trained on
functionally non-validated datasets, underscoring the importance of
high-quality datasets in RTL code generation.
