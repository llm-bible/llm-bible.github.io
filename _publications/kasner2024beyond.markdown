---
layout: publication
title: 'Beyond Traditional Benchmarks: Analyzing Behaviors Of Open Llms On Data-to-text Generation'
authors: Kasner Zdeněk, Dušek Ondřej
conference: "Arxiv"
year: 2024
bibkey: kasner2024beyond
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.10186"}
tags: ['Applications', 'GPT', 'Language Modeling', 'Model Architecture', 'Tools', 'Training Techniques']
---
We analyze the behaviors of open large language models (LLMs) on the task of data-to-text (D2T) generation, i.e., generating coherent and relevant text from structured data. To avoid the issue of LLM training data contamination with standard benchmarks, we design Quintd - a tool for collecting novel structured data records from public APIs. We find that open LLMs (Llama 2, Mistral, and Zephyr) can generate fluent and coherent texts in zero-shot settings from data in common formats collected with Quintd. However, we show that the semantic accuracy of the outputs is a major issue: both according to human annotators and our reference-free metric based on GPT-4, more than 80&#37; of the outputs of open LLMs contain at least one semantic error. We publicly release the code, data, and model outputs.
