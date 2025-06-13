---
layout: publication
title: 'Rethinking Table Instruction Tuning'
authors: Naihao Deng, Rada Mihalcea
conference: "Arxiv"
year: 2025
bibkey: deng2025rethinking
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2501.14693'}
tags: ['Training Techniques', 'Model Architecture', 'GPT', 'Fine-Tuning', 'Reinforcement Learning']
---
Recent advances in table understanding have focused on instruction-tuning
large language models (LLMs) for table-related tasks. However, existing
research has overlooked the impact of hyperparameter choices and lacks a
comprehensive evaluation of the out-of-domain table understanding ability and
the general capabilities of these table LLMs. In this paper, we evaluate these
abilities in existing table LLMs, and reveal significant declines in both
out-of-domain table understanding and general capabilities compared to their
base models. Through systematic analysis, we show that hyperparameters, such as
learning rate, can significantly influence both table-specific and general
capabilities. Contrary to the existing table instruction-tuning works, we
demonstrate that smaller learning rates and fewer training instances can
enhance table understanding while preserving general capabilities. Based on our
findings, we introduce TAMA, a TAble LLM instruction-tuned from LLaMA 3.1 8B
Instruct, which achieves performance on par with, or surpassing GPT-3.5 and
GPT-4 on table tasks, while maintaining strong out-of-domain generalization and
general capabilities. Our findings highlight the potential for reduced data
annotation costs and more efficient model development through careful
hyperparameter selection.
