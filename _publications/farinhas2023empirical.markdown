---
layout: publication
title: 'An Empirical Study Of Translation Hypothesis Ensembling With Large Language Models'
authors: António Farinhas, José G. C. De Souza, André F. T. Martins
conference: "Arxiv"
year: 2023
bibkey: farinhas2023empirical
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2310.11430'}
tags: ['GPT', 'Applications', 'Model Architecture', 'Prompting', 'Survey Paper']
---
Large language models (LLMs) are becoming a one-fits-many solution, but they
sometimes hallucinate or produce unreliable output. In this paper, we
investigate how hypothesis ensembling can improve the quality of the generated
text for the specific problem of LLM-based machine translation. We experiment
with several techniques for ensembling hypotheses produced by LLMs such as
ChatGPT, LLaMA, and Alpaca. We provide a comprehensive study along multiple
dimensions, including the method to generate hypotheses (multiple prompts,
temperature-based sampling, and beam search) and the strategy to produce the
final translation (instruction-based, quality-based reranking, and minimum
Bayes risk (MBR) decoding). Our results show that MBR decoding is a very
effective method, that translation quality can be improved using a small number
of samples, and that instruction tuning has a strong impact on the relation
between the diversity of the hypotheses and the sampling temperature.
