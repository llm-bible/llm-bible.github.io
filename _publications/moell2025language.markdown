---
layout: publication
title: 'Language Complexity Measurement As A Noisy Zero-shot Proxy For Evaluating LLM Performance'
authors: Birger Moell, Johan Boye
conference: "Arxiv"
year: 2025
bibkey: moell2025language
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.11578"}
tags: ['RAG', 'GPT', 'Model Architecture']
---
Large Language Models (LLMs) have made significant strides in natural
language generation but often face challenges in tasks requiring precise
calculations and structural analysis. This paper investigates the performance
of state-of-the-art LLMs on language complexity measurement tasks, through the
computation of the LIX readability metric and Average Dependency Distance
(ADD). Using Swedish high school and university-level essays, we evaluate the
models' abilities to compute LIX scores and perform dependency parsing,
comparing their results to established ground truths. Our findings reveal that
while all models demonstrate some capacity for these tasks, ChatGPT-o1-mini
performs most consistently, achieving the highest accuracy in both LIX
computation and dependency parsing. Additionally, we observe a strong
significant correlation -0.875 p 0.026 (N=6) between the models' accuracy in
computing LIX and their overall performance on the Massive Multitask Language
Understanding (MMLU) benchmark. These results suggest that language complexity
measurement abilities can serve as a noisy zero-shot proxies for assessing the
general capabilities of LLMs, providing a practical method for model evaluation
without the need for extensive benchmarking datasets.
