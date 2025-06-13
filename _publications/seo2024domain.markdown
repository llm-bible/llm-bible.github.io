---
layout: publication
title: 'DAHL: Domain-specific Automated Hallucination Evaluation Of Long-form Text Through A Benchmark Dataset In Biomedicine'
authors: Jean Seo, Jongwon Lim, Dongjun Jang, Hyopil Shin
conference: "Arxiv"
year: 2024
bibkey: seo2024domain
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.09255"}
tags: ['Language Modeling', 'Applications', 'RAG']
---
We introduce DAHL, a benchmark dataset and automated evaluation system
designed to assess hallucination in long-form text generation, specifically
within the biomedical domain. Our benchmark dataset, meticulously curated from
biomedical research papers, consists of 8,573 questions across 29 categories.
DAHL evaluates fact-conflicting hallucinations in Large Language Models (LLMs)
by deconstructing responses into atomic units, each representing a single piece
of information. The accuracy of these responses is averaged to produce the DAHL
Score, offering a more in-depth evaluation of hallucinations compared to
previous methods that rely on multiple-choice tasks. We conduct experiments
with 8 different models, finding that larger models tend to hallucinate less;
however, beyond a model size of 7 to 8 billion parameters, further scaling does
not significantly improve factual accuracy. The DAHL Score holds potential as
an efficient alternative to human-annotated preference labels, being able to be
expanded to other specialized domains. We release the dataset and code in
public.
