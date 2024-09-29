---
layout: publication
title: 'Performance Trade-offs Of Watermarking Large Language Models'
authors: Ajith Anirudh, Singh Sameer, Pruthi Danish
conference: "Arxiv"
year: 2023
bibkey: ajith2023performance
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.09816"}
tags: ['Applications', 'Language Modeling', 'RAG']
---
Amidst growing concerns of large language models (LLMs) being misused for generating misinformation or completing homework assignments watermarking has emerged as an effective solution for distinguishing human-written and LLM-generated text. A prominent watermarking strategy is to embed a signal into generated text by upsampling a (pseudorandomly-chosen) subset of tokens at every generation step. Although this signal is imperceptible to a human reader it is detectable through statistical testing. However implanting such signals alters the models output distribution and can have unintended effects when watermarked LLMs are used for downstream applications. In this work we evaluate the performance of watermarked LLMs on a diverse suite of tasks including text classification textual entailment reasoning question answering translation summarization and language modeling. We find that watermarking has negligible impact on the performance of tasks posed as k-class classification problems in the average case. However the accuracy can plummet to that of a random classifier for some scenarios (that occur with non-negligible probability). Tasks that are cast as multiple-choice questions and short-form generation are surprisingly unaffected by watermarking. For long-form generation tasks including summarization and translation we see a drop of 15-2037; in the performance due to watermarking. Our findings highlight the trade-offs that users should be cognizant of when using watermarked models and point to cases where future research could improve existing trade-offs.
