---
layout: publication
title: 'Mistral 7B'
authors: Jiang Albert Q., Sablayrolles Alexandre, Mensch Arthur, Bamford Chris, Chaplot Devendra Singh, Casas Diego De Las, Bressand Florian, Lengyel Gianna, Lample Guillaume, Saulnier Lucile, Lavaud Lélio Renard, Lachaux Marie-anne, Stock Pierre, Scao Teven Le, Lavril Thibaut, Wang Thomas, Lacroix Timothée, Sayed William El
conference: "Arxiv"
year: 2023
bibkey: jiang2023mistral
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.06825"}
tags: ['Applications', 'Attention Mechanism', 'Efficiency And Optimization', 'Model Architecture', 'RAG']
---
We introduce Mistral 7B v0.1, a 7-billion-parameter language model engineered
for superior performance and efficiency. Mistral 7B outperforms Llama 2 13B
across all evaluated benchmarks, and Llama 1 34B in reasoning, mathematics, and
code generation. Our model leverages grouped-query attention (GQA) for faster
inference, coupled with sliding window attention (SWA) to effectively handle
sequences of arbitrary length with a reduced inference cost. We also provide a
model fine-tuned to follow instructions, Mistral 7B -- Instruct, that surpasses
the Llama 2 13B -- Chat model both on human and automated benchmarks. Our
models are released under the Apache 2.0 license.
