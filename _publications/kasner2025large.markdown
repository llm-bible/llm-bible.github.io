---
layout: publication
title: 'Large Language Models As Span Annotators'
authors: Zdeněk Kasner, Vilém Zouhar, Patrícia Schmidtová, Ivan Kartáč, Kristýna Onderková, Ondřej Plátek, Dimitra Gkatzia, Saad Mahamood, Ondřej Dušek, Simone Balloccu
conference: "Arxiv"
year: 2025
bibkey: kasner2025large
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.08697'}
tags: ['RAG', 'Language Modeling', 'Interpretability and Explainability', 'Applications']
---
For high-quality texts, single-score metrics seldom provide actionable
feedback. In contrast, span annotation - pointing out issues in the text by
annotating their spans - can guide improvements and provide insights. Until
recently, span annotation was limited to human annotators or fine-tuned encoder
models. In this study, we automate span annotation with large language models
(LLMs). We compare expert or skilled crowdworker annotators with open and
proprietary LLMs on three tasks: data-to-text generation evaluation, machine
translation evaluation, and propaganda detection in human-written texts. In our
experiments, we show that LLMs as span annotators are straightforward to
implement and notably more cost-efficient than human annotators. The LLMs
achieve moderate agreement with skilled human annotators, in some scenarios
comparable to the average agreement among the annotators themselves.
Qualitative analysis shows that reasoning models outperform their
instruction-tuned counterparts and provide more valid explanations for
annotations. We release the dataset of more than 40k model and human
annotations for further research.
