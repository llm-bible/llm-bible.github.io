---
layout: publication
title: 'Lost In Cultural Translation: Do Llms Struggle With Math Across Cultural Contexts?'
authors: Aabid Karim, Abdul Karim, Bhoomika Lohana, Matt Keon, Jaswinder Singh, Abdul Sattar
conference: "Arxiv"
year: 2025
bibkey: karim2025lost
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.18018'}
  - {name: "Code", url: 'https://github.com/akarim23131/Lost_in_Cultural_Translation'}
tags: ['Has Code', 'Security', 'Training Techniques', 'Applications', 'Tools', 'Reinforcement Learning']
---
Large Language Models (LLMs) have significantly advanced various fields,
particularly coding, mathematical reasoning, and logical problem solving.
However, a critical question remains: Do these mathematical reasoning abilities
persist when LLMs are presented with culturally adapted math problems?
Specifically, how do LLMs perform when faced with math problems embedded in
cultural contexts that have no significant representation in main stream
web-scale AI training data? To explore this, we generated six synthetic
cultural datasets from GSM8K, a widely used benchmark for assessing LLMs'
mathematical reasoning skills. While preserving the mathematical logic and
numerical values of the original GSM8K test set, we modify cultural elements
such as personal names, food items, place names, etc. These culturally adapted
datasets provide a more reliable framework for evaluating LLMs' mathematical
reasoning under shifting cultural contexts. Our findings reveal that LLMs
struggle with math problems when cultural references change, even though the
underlying mathematical structure remains constant. Smaller models exhibit
greater performance drops compared to larger models. Interestingly, our results
also suggest that cultural familiarity can enhance mathematical reasoning. Even
models with no explicit mathematical training but exposure to relevant cultural
contexts sometimes outperform larger, mathematically proficient models on
culturally embedded math problems. This study highlights the impact of cultural
context on the mathematical reasoning abilities of LLMs, underscoring the need
for more diverse and representative training data to improve robustness in
real-world applications. The benchmark data sets and script for reproducing the
results are available at
https://github.com/akarim23131/Lost_in_Cultural_Translation
