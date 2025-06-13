---
layout: publication
title: 'Pensez: Less Data, Better Reasoning -- Rethinking French LLM'
authors: Huy Hoang Ha
conference: "Arxiv"
year: 2025
bibkey: ha2025less
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.13661"}
tags: ['Fine-Tuning', 'Training Techniques', 'Pretraining Methods']
---
Large language models (LLMs) have demonstrated remarkable capabilities in
various natural language processing tasks. However, achieving strong
performance in specialized domains like mathematical reasoning and non-English
languages often requires extensive training on massive datasets. This paper
investigates a contrasting approach: strategic fine-tuning on a small,
high-quality, bilingual (English-French) dataset to enhance both the reasoning
capabilities and French language proficiency of a large language model. Rather
than relying on scale, we explore the hypothesis that targeted data curation
and optimized training can achieve competitive, or even superior, performance.
We demonstrate, through targeted supervised fine-tuning (SFT) on only 2,000
carefully selected samples, significant improvements in mathematical reasoning.
Specifically, Pensez 7B exhibits an increase in accuracy of the base model up
to 20% on the AIME25 and a 12% increase on a French MATH level 5 benchmark.
These results challenge the prevailing assumption that massive datasets are
aprerequisite for strong reasoning performance in LLMs, highlighting the
potential of strategic data curation and optimized fine-tuning for enhancing
both specialized skills and multilingual capabilities. Our findings have
implications for the efficient development of high-performing, multilingual
LLMs, especially in resource-constrained scenarios.
