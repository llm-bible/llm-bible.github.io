---
layout: publication
title: 'Quasi-random Multi-sample Inference For Large Language Models'
authors: Aditya Parashar, Aditya Vikram Singh, Avinash Amballa, Jinlin Lai, Benjamin Rozonoyer
conference: "Arxiv"
year: 2024
bibkey: parashar2024quasi
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.06251"}
tags: ['Language Modeling', 'Applications', 'WMT']
---
Large language models (LLMs) are often equipped with multi-sample decoding
strategies. An LLM implicitly defines an arithmetic code book, facilitating
efficient and embarrassingly parallelizable \textbf\{arithmetic sampling\} to
produce multiple samples using quasi-random codes. Traditional text generation
methods, such as beam search and sampling-based techniques, have notable
limitations: they lack parallelizability or diversity of sampled sequences.
This study explores the potential of arithmetic sampling, contrasting it with
ancestral sampling across two decoding tasks that employ multi-sample
inference: chain-of-thought reasoning with self-consistency and machine
translation with minimum Bayes risk decoding. Our results demonstrate that
arithmetic sampling produces more diverse samples, significantly improving
reasoning and translation performance as the sample size increases. We observe
a \\(\mathbf\{3\text\{-\}5%\}\\) point increase in accuracy on the GSM8K dataset and a
\\(\mathbf\{0.45\text\{-\}0.89%\}\\) point increment in COMET score for WMT19 tasks
using arithmetic sampling without any significant computational overhead.
