---
layout: publication
title: 'Transformer-based Language Models For Reasoning In The Description Logic ALCQ'
authors: Angelos Poulis, Eleni Tsalapati, Manolis Koubarakis
conference: "Arxiv"
year: 2024
bibkey: poulis2024transformer
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.09613"}
tags: ['Transformer', 'GPT', 'RAG', 'Model Architecture', 'Pretraining Methods', 'BERT', 'Few-Shot', 'Prompting', 'In-Context Learning']
---
Recent advancements in transformer-based language models have sparked
research into their logical reasoning capabilities. Most of the benchmarks used
to evaluate these models are simple: generated from short (fragments of)
first-order logic sentences with only a few logical operators and quantifiers.
We construct the natural language dataset, DELTA\\(_D\\), using the expressive
description logic language \\(\mathcal\{ALCQ\}\\). DELTA\\(_D\\) comprises 384K examples
and increases in two dimensions: i) reasoning depth, and ii) linguistic
complexity. In this way, we systematically investigate the logical reasoning
capabilities of a supervised fine-tuned DeBERTa-based model and two large
language models (GPT-3.5, GPT-4) with few-shot prompting. We show that the
DeBERTa-based model fine-tuned on our dataset can master the entailment
checking task. Moreover, the performance of GPTs can improve significantly even
when a small number of samples is provided (9 shots). We open-source our code
and datasets.
