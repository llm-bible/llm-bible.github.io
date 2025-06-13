---
layout: publication
title: 'Topic-based Watermarks For Large Language Models'
authors: Alexander Nemecek, Yuzhou Jiang, Erman Ayday
conference: "Arxiv"
year: 2024
bibkey: nemecek2024topic
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2404.02138'}
tags: ['Prompting', 'Security', 'Training Techniques', 'Tools']
---
The indistinguishability of Large Language Model (LLM) output from
human-authored content poses significant challenges, raising concerns about
potential misuse of AI-generated text and its influence on future AI model
training. Watermarking algorithms offer a viable solution by embedding
detectable signatures into generated text. However, existing watermarking
methods often entail trade-offs among attack robustness, generation quality,
and additional overhead such as specialized frameworks or complex integrations.
We propose a lightweight, topic-guided watermarking scheme for LLMs that
partitions the vocabulary into topic-aligned token subsets. Given an input
prompt, the scheme selects a relevant topic-specific token list, effectively
"green-listing" semantically aligned tokens to embed robust marks while
preserving the text's fluency and coherence. Experimental results across
multiple LLMs and state-of-the-art benchmarks demonstrate that our method
achieves comparable perplexity to industry-leading systems, including Google's
SynthID-Text, yet enhances watermark robustness against paraphrasing and
lexical perturbation attacks while introducing minimal performance overhead.
Our approach avoids reliance on additional mechanisms beyond standard text
generation pipelines, facilitating straightforward adoption, suggesting a
practical path toward globally consistent watermarking of AI-generated content.
